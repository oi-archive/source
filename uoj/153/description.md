# 题目描述

<p>picks 博士轻松地做出了魔仙堡女王的题目，并利用巴拉拉能量成功地修好了时光机器。但是这时他发现他已经迷失在了无数条世界线里，难以回到他原来处在的世界线的过去了。</p>
<p>为了回到正确的过去，picks 博士观测了 $n$ 个过去和 $n$个未来。经过 picks 博士的研究，他发现存在一个 1 到 $n$ 的排列 $A$，使得对于每一个 $i$ 都存在一条世界线连接着第 $i$ 个过去和第 $A_i$ 个未来。现在 picks 博士想要通过实验得到排列 $A$。</p>

# 任务


<p>因为有关世界线的理论非常复杂，所以 picks 博士的实验同样非常繁琐——他甚至用了不止一轮实验才得到了答案。但是我们可以把实验过程简化得到一道这样的题目：</p>
<p>这是一道交互题，在交互库中生成了一个长度为 $n$ 的置换 $A$，你需要编写一个函数 query_permutation 来得到这个置换，<strong>题面比较长，请大家耐心阅读</strong>。</p>
<ul><li>query_permutation(n, ans)<ul><li>n：置换 $A$ 的长度，保证 $n \geq 1$。</li>
<li>ans：一个 int 数组，你需要把你得到的排列 $A$ 的第 $i$ 项存到 $ans[i]$ 中作为结果，其中 $1 \leq i \leq n$，并返回 1。如果你发现无论如何都无法唯一确定排列 $A$，那么就返回 $0$。</li>
</ul></li>
</ul><p>你可以四个函数 new_round、next_step、addedge、query 来帮助你确定这个排列。</p>
<ul><li>new_round() 调用这个函数后，将开始新的一轮实验，新的实验默认阶段为 $1$。</li>
<li>next_step() 调用这个函数后，实验将进入下一个阶段。</li>
<li>addedge(u,v) 这个函数只能在每一轮实验的第一个阶段使用，表示在第 $u$ 个点和第 $v$ 个点之间连一条边。如果 $u$ 或者 $v$ 不在范围 $[1,n]$ 之内，这次操作将会被忽略。</li>
<li>query(u,v) 将返回 $u+n$ 和 $v+n$ 的连通性，如果联通则返回 $1$，否则返回 $0$。如果 $u$ 或者 $v$ 不在范围 $[1,n]$ 之内，将会返回 0。</li>
</ul><p>接下来是交互过程的详细介绍，你可以结合样例一以及样例程序来帮助理解。</p>
<p>当你调用函数new_round的时候，将开始一轮新的实验。这时交互库中会生成一个 $2n$ 个点的无向图，初始状态下有 $n$ 条边，第 $i$ 条边连接了点 $i$ 和点 $A_i+n$。每一轮实验可以分成两个阶段：</p>
<ol><li>这个阶段在调用new_round后自动进入，<strong>你只能在每一轮实验的这一个阶段内调用函数 addedge</strong>。每当你调用一次函数 addedge(u,v)，交互库将会在图中的第 $u$ 个点和第 $v$ 个点之间连上一条无向边。如果在这个阶段内调用了函数 next_step，那么将会进入第二个阶段。<strong>这个阶段内不允许调用函数 query 和 new_round。</strong></li>
<li><strong>你只能在每一轮实验的这一个阶段内调用函数 query</strong>。每当你调用一次函数 query(u,v)，交互库将会返回图中第 $u+n$ 个点和第 $v+n$ 个点之间的连通性。如果在这个阶段内调用了函数 new_round，将会重新开始一轮新的实验。<strong>这个阶段不允许调用函数 addedge 和 next_step。</strong></li>
</ol><p><strong>如果你已经得到了答案，那么你可以在任意一轮实验的任意一个阶段返回答案。</strong></p>
<p>picks 博士的巴拉拉能量是有限的，因此为了节约能源，他规定实验最多进行两轮，即你最多只能调用两次函数 new_round（<strong>注意：程序开始必须调用一次new_round</strong>）。</p>
<p>同时，picks博士发现调用函数 query 也是会消耗巴拉拉能量的，因此他想让你尽可能地减少函数 query 的调用次数。</p>

# 实现细节


<p>本题只支持 C/C++/Pascal。</p>
<p>你只能提交一个源文件实现如上所述的 query_permutation 函数，并且遵循下面的命名和接口。</p>
<h4>C/C++</h4>
<p>你需要包含头文件 worldline.h。</p>
<pre><code class="sh_cpp">int query_permutation(int n, int ans[]);</code></pre>
<p>函数 new_round, next_step, addedge, query 的接口信息如下。</p>
<pre><code class="sh_cpp">void new_round();
void next_step();
void addedge(int u, int v);
int query(int u, int v);</code></pre>
<h4>Pascal</h4>
<p>你需要使用单元 graderhelperlib。</p>
<pre><code class="sh_pascal">function query_permutation(n: longint; var ans: array of longint) : longint;</code></pre>
<p>函数 new_round, next_step, addedge, query 的接口信息如下。</p>
<pre><code class="sh_pascal">procedure new_round;
procedure next_step;
procedure addedge(u, v: longint);
function query(u, v: longint): longint;</code></pre>
<p>如果有不清楚的地方，见样例及测评库下载，<strong>内附了样例程序，样例程序按照样例一的解释调用函数</strong>。</p>
<p><strong>如果你不会本地调试交互题，可以点开UOJ的FAQ。</strong></p>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ol><li>第 $1$ 行：一个正整数$T$，表示数据组数。</li>
<li>每组数据的第 $1$ 行：一个正整数 $n$。</li>
<li>每组数据的第 $2$ 行：$n$ 个正整数，第 $i$ 个整数表示 $A_i$。</li>
</ol><p>对每组测试数据我们都会调用一次函数 query_permutation，并对每组测试数据评测系统都会输出两行：</p>
<p>第一行是四个空格隔开的整数，分别表示你调用函数过程是否合法（如果合法输出1，否则输出0），你的返回值，query 函数的调用次数以及 addedge 函数的调用次数。</p>
<p>第二行是 $n$ 个空格隔开的整数，表示你找到的排列 $A$，如果你的函数的返回值是 $0$，那么这 $n$ 个数都将是 $0$。</p>

# 样例一


<h4>input</h4>
<pre>2
3
2 1 3
2
1 2

</pre>

<h4>output</h4>
<pre>1 1 6 2
2 1 3
1 0 0 0
0 0

</pre>

<h4>explanation</h4>
<p>对于第一组数据：</p>
<p>第一轮实验我们采取如下操作方式：在第一阶段连上无向边 $(1,2)$，然后在第二阶段两两查询连通性，我们发现此时的联通块是 $\{4,5\}$ 和 $\{6\}$。</p>
<p>第二轮实验我们采取如下操作方式：在第一阶段连上无向边 $(2,3)$，然后在第二阶段两两查询连通性，我们发现此时的联通块是 $\{4,6\}$ 和 $\{5\}$。</p>
<p>由此我们可以推导出原来的排列是 $2\ 1\ 3$。此时我们确定了一个排列，所以函数的返回值是 $1$。在整个过程中调用了 $2$ 次函数 addedge 和 $6$ 次函数 query。</p>
<p>对于第二组数据：</p>
<p>我们发现此时无论怎么进行实验，都无法区分排列 $1\ 2$ 和排列 $2\ 1$，所以返回 $0$。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>共 $10$ 个测试点，每个测试点 $10$ 分。</p>
<p>对于每一个测试点，你得程序必须满足如下条件，才能获得 $10$ 分，否则得 $0$ 分：</p>
<ol><li>对于每一组数据，函数调用都是合法的。</li>
<li>对于每一组数据，query 函数和 addedge 函数的调用次数都不会超过 $2 \times 10^6$ 次。</li>
</ol><div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$ 的规模</th></tr></thead><tbody><tr><td>1</td><td>$n = 4$</td></tr><tr><td>2</td><td>$n = 5$</td></tr><tr><td>3</td><td>$n = 990$</td>
            </tr><tr><td>4</td><td>$n = 1000$</td></tr><tr><td>5</td><td>$n = 4950$</td></tr><tr><td>6</td><td>$n=5000$</td></tr><tr><td>7</td><td>$n=5050$</td></tr><tr><td>8</td><td rowspan="3">$n \leq 10000$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，保证有 $n \geq 1，T \leq 10$，以上的 $10$ 个测试点都满足 $T=10$。</p>
<p><strong>如果这题场上有人 AC，那么我们会给所有在比赛时通过了这题的选手中，后三个点调用 query 函数总数最少的人赠送萌萌哒 UOJ 抱枕一个！</strong></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=153">样例数据下载</a></p>
