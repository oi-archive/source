# 题目描述

<p><strong>这是一道交互题。</strong></p>
<p>出题人 02 喜欢网上冲浪。可是这天，他所在的小区的网络坏掉了，于是他喊来了你帮忙修一修。</p>
<p>小区的网络由 $N$ 个网络结点和 $M$ 条信道组成，可以被看作是一张 $N$ 个点 $M$ 条边的<strong>无向简单图</strong>（简单图满足任意两点之间至多存在一条直接相连的边，且没有自环）。点从 $1 \sim N$ 编号，边从 $1 \sim M$ 编号。目前，你只知道信道的总数是 $M$，并且还掌握着每条信道的管理权限，然而你<strong>并不知道</strong>每条信道连接着哪两个结点。</p>
<p>为了恢复出网络结构，你可以使用一种土办法：重启大法！</p>
<p>当然重启也是需要智慧的。具体来说，你可以进行若干次操作，每次操作方式如下：</p>
<ol><li>给每个结点 $i$ 标上一个自己定的权值 $a_i$；</li>
<li>选取一个信道的子集 $S$，把不在 $S$ 里的信道都关闭，只让 $S$ 里的信道保持开启状态；</li>
<li>此时，每个结点 $i$ 会自动计算出与 $i$ <strong>通过开启状态的信道直接相邻的</strong>所有点 $v$ 的 $a_v$ 异或和，记为 $b_i$；</li>
<li>你通过管理员权限获取所有结点的 $b_i$ 值，然后关闭的信道都重启，网络恢复至原状。</li>
</ol><p>请你在不超过 $50$ 次操作内，求出所有信道构成的集合。</p>
<p><strong>注意，你只需要求出信道的集合。即，你只需要恢复出哪些结点之间有信道，不用恢复出每条信道对应的编号。</strong></p>

# 实现细节


<p>你不需要，也不应该实现主函数，<strong>你只需要</strong>实现函数 $\texttt{Solve(N, M)}$，这里的 $\texttt{N}$ 和 $\texttt{M}$ 分别表示结点和信道的个数。你可以通过调用如下函数来和交互库进行交互：</p>
<ol><li>$\texttt{Query(A,S)}$<ul><li>这个函数可以暂时删去编号不在 $S$ 中的信道，并将 $i$ 号点的 $a_i$ 设置成 $A[i-1]$；</li>
<li>交互库会返回一个大小为$N$的 <code>vector</code> $B$，$B[i-1]$ 表示 $i$ 号点的 $b_i$；</li>
<li>你需要保证 对 $S$ 中的任意元素 $x$，有 $1 \le x \le M$且互不相同，同时你需要保证 $A$ 的大小恰好为$N$；</li>
<li>$A, S, B$ 均为 <code>vector</code>；</li>
<li>$A, B$ 中元素类型为 <code>unsigned long long</code>，$S$中元素类型为 <code>int</code>。</li>
</ul></li>
<li>$\texttt{Report(x, y)}$<ul><li>这个函数可以向交互库汇报一条你发现的连接 $x$ 和 $y$ 的信道；</li>
<li>你需要保证 $1 \le x,y \le N$；</li>
<li>$x,y$ 均为 <code>int</code>；</li>
<li>你必须恰好将所有信道报告一次，否则你的程序将会判定为错误。</li>
</ul></li>
</ol><p>评测时，交互库会<strong>恰好</strong>调用 $\texttt{Solve}$ 一次。</p>
<p><strong>本题保证所使用的图在交互开始之前已经完全确定，不会根据和你的程序的交互过程动态构造，因此题目中的交互操作都是确定性的，你不需要关心这些操作在交互库中的具体实现。</strong></p>
<p><strong>生成数据时，图是按一定方式从 $N$ 个点，$M$ 条边的简单无向图中随机选取的（见限制与约定一节）。</strong></p>
<p><strong>数据保证在调用次数限制下，交互库运行所需的时间不超过 2.5s；交互库使用的内存大小固定，且不超过 128MB。</strong></p>

# 实现方法


<p>本题仅支持 C++ 语言。
附加文件中已经提供了一个 <code>template_explore.cpp</code>，请将这个文件拷贝一份，重命名为 <code>explore.cpp</code>，然后在其基础上答题。</p>
<ul><li>请确保你的程序开头有 <code>#include &#34;explore.h&#34;</code>。</li>
<li>你需要实现的函数 $\texttt{Solve}$ 的接口信息如下：<ul><li><code>void Solve(int N, int M);</code></li>
</ul></li>
<li>你可以调用的交互函数的接口如下：<ul><li><code>vector&lt;unsigned long long&gt; Query(vector&lt;unsigned long long&gt; A, vector&lt;int&gt; S);</code></li>
<li><code>void Report(int x,int y);</code></li>
</ul></li>
</ul>
# 测试程序方式


<p><strong>试题目录下的 <code>grader.cpp</code> 是我们提供的交互库参考实现，最终测试时所用的交互库实现与该参考实现有所不同，因此选手的解法不应该依赖交互库实现。</strong></p>
<ol><li>编译方法：<ul><li>你需要在本题目录下使用如下命令编译得到可执行程序：<ul><li><code>g++ grader.cpp explore.cpp -o explore -O2 -lm</code></li>
</ul></li>
</ul></li>
<li>对于编译得到的可执行程序：<ul><li>可执行文件将从<strong>标准输入</strong>读入以下格式的数据：<ul><li>第一行包含两个整数 $N, M$，意义如题面描述。</li>
<li>接下来 $M$ 行，每行两个整数 $x, y$，描述一条连接 $x$ 号点与 $y$ 号点的无向边。</li>
</ul></li>
<li>读入完成之后，交互库将调用恰好一次函数 $\texttt{Solve}$，用输入的数据测试你的函数。你的函数正确返回后，交互库会判断你的计算是否正确，若正确则会输出 <code>Correct</code> ，否则会输出相应的错误信息。</li>
</ul></li>
</ol><p>假设可执行文件读入的数据为：</p>
<pre><code class="sh_plain">3 2
1 2
2 3</code></pre>
<p>数据第一行的两个整数分别表示点数和边条数，即 $N = 3 , M = 2$。</p>
<p>$\texttt{Query(S, A)}$ 调用次数不能超过 50 次。</p>
<p>下面是一个正确的交互过程：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>选手程序</th><th>交互库</th><th>说明</th></tr></thead><tbody><tr><td></td><td>调用 $\texttt{Solve(3, 2)}$</td><td>开始测试</td></tr><tr><td>调用 $\texttt{Query}(\{1,2,4\},\{1\})$</td><td>返回 $\{2,1,0\}$</td><td>$1$ 号节点权值为 $a[2]=2$,
$2$号节点权值为$a[1]=1$,
$3$号节点权值为$0$</td></tr><tr><td>调用 $\texttt{Query}(\{1,2,4\},\{1,2\})$</td><td>返回 $\{2,5,2\}$</td><td>$1$ 号节点权值为 $a[2]=2$,
$2$号节点权值为$a[1] \mathbin{\mathrm{xor}} a[3]=5$,
$3$号节点权值为$a[2]=2$</td></tr><tr><td>调用 $\texttt{report}(1, 2)$</td><td></td><td>发现了信道 $(1, 2)$ 并记录</td></tr><tr><td>调用 $\texttt{report}(3, 2)$</td><td></td><td>发现了信道 $(3, 2)$ 并记录</td></tr><tr><td>运行结束并返回</td><td>向屏幕打印 Correct </td><td>交互结束，结果正确</td></tr></tbody></table></div>


# 样例一


<p>见附加文件下载</p>

# 样例二


<p>见附加文件下载</p>

# 评分方式


<p>最终评测<strong>只会</strong>收取 <code>explore.cpp</code>，修改选手目录下其他文件对评测<strong>无效</strong>。</p>
<p><strong>本题首先会受到和传统题相同的限制</strong>。例如编译错误会导致整道题目得 $0$ 分，运行时错误、超过时间限制、超过空间限制等会导致相应测试点得 $0$ 分等。你只能访问自己定义的和交互库给出的变量及其对应的内存空间，尝试访问其他空间将可能导致编译错误或运行错误。</p>
<p>在上述条件基础上，在一个测试点中，你得到满分，当且仅当：</p>
<ol><li>你的每次函数调用均合法，且调用 $\texttt{Query},\texttt{Report}$ 的次数分别不超过 $50$，$M$ 次。</li>
<li>由于 $\texttt{Report}$ 的调用次数限制为 $M$，你的每次调用都必须记录一条新的且存在的边；即每次调用 $\texttt{report(x, y)}$ 时，应满足：有一条连接 $x$ 号点和 $y$ 号点的路径，且在这次调用之前从未调用过 $\texttt{report(x, y)}$ 或 $\texttt{report(y, x)}$。</li>
<li>你实现的函数 $\texttt{Solve}$ 正常返回。</li>
<li>在 $\texttt{Solve}$ 函数返回时，你已经通过调用 $\texttt{Report}$ 记录了全部 $M$ 条信道。</li>
</ol>
# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$N$</th><th>$M$</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1$</td><td>$N=20$</td><td>$M=50$</td><td rowspan="4">无</td></tr><tr><td>$2$</td><td>$N=60$</td><td>$M=300$</td></tr><tr><td>$3$</td><td>$N=3000$</td><td>$M=10000$</td></tr><tr><td>$4$</td><td>$N=6000$</td><td>$M=30000$</td></tr><tr><td>$5$</td><td>$N=49998$</td><td>$M=49997$</td><td rowspan="2">图为连通图</td></tr><tr><td>$6$</td><td>$N=49999$</td><td>$M=49999$</td></tr><tr><td>$7$</td><td rowspan="2">$N=50000$</td><td>$M=50000$</td><td rowspan="4">无</td></tr><tr><td>$8$</td><td rowspan="3">$M=300000$</td></tr><tr><td>$9$</td><td>$N=15000$</td></tr><tr><td>$10$</td><td>$N=10000$</td></tr></tbody></table></div>

<p>对于 5, 6 号测试点，保证按照如下方式随机生成:</p>
<ul><li>均匀随机一条不在图中的非自环的边 $(u, v)$。</li>
<li>如果加入 $(u, v)$ 后，无论之后再怎么加边，都无法使得最终的图是个连通图，那么就不加入这条边；否则加入这条边。</li>
<li>重复操作直至加入恰好$M$条边为止。</li>
</ul><p>对于其他测试数据，保证按照如下方式随机生成：</p>
<ul><li>均匀随机一条不在图中的非自环的边 $(u, v)$。</li>
<li>重复操作直至加入恰好$M$条边为止。</li>
</ul><p><strong>时间限制</strong>：$4\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 提示


<p>你的程序可以通过判断传入的 $N$ 的个位来区分上述不同的数据类型。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=550">附加文件下载</a></p>
