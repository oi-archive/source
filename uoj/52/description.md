# 题目描述

<p>刚刚越过绝境长城，只见天空中出现了炫目的光芒 —— 圣诞老人出现了。</p>
<p>元旦三侠立刻进入战斗。生蛋侠、圆蛋侠和零蛋侠分别有 $n_a, n_b, n_c$ 个激光炮。生蛋侠的激光炮的威力分别为 $a_0, a_1, \dots, a_{n_a - 1}$，圆蛋侠的激光炮的威力分别为 $b_0, b_1, \dots, b_{n_b - 1}$，零蛋侠的激光炮的威力分别为 $c_0, c_1, \dots, c_{n_c - 1}$。</p>
<p>元旦三侠的激光炮的威力<strong>已经按从小到大的顺序排好序了</strong>，即 $a_{i - 1} \leq a_i$，$b_{i - 1} \leq b_i$，$c_{i - 1} \leq c_i$。</p>
<p>由于元旦三侠精力有限，他们得废弃掉 $k$ 个激光炮。为了更好地进行战斗，他们决定废弃掉威力前 $k$ 小的激光炮。</p>
<p>赶快帮助元旦三侠，让激光炮投入战斗吧！你只需要告诉他们威力第 $k$ 小的激光炮威力是多少。</p>

# 任务


<p>你需要编写一个函数 query_kth，以确定威力值第 $k$ 小的激光炮威力值是多少。</p>
<ul><li>query_kth(n_a, n_b, n_c, k)<ul><li>n_a：生蛋侠拥有的激光炮数目 $n_a$。保证 $n_a \geq 0$。</li>
<li>n_b：圆蛋侠拥有的激光炮数目 $n_b$。保证 $n_b \geq 0$。</li>
<li>n_c：零蛋侠拥有的激光炮数目 $n_c$。保证 $n_c \geq 0$。</li>
<li>$k$：要查询的排名 $k$。保证 $1 \leq k \leq n_a + n_b + n_c$。</li>
</ul></li>
</ul><p>你可以调用三个函数 get_a、get_b、get_c 以帮助你确定第 $k$ 小的激光炮。我们会根据你调用这三个函数的<strong>总次数</strong>评分。</p>
<ul><li>get_a(i) 将返回 $a_i$。如果 $i$ 在 $0 \leq i &lt; n_a$ 之外，该函数将返回 $2147483647$。</li>
<li>get_b(i) 将返回 $b_i$。如果 $i$ 在 $0 \leq i &lt; n_b$ 之外，该函数将返回 $2147483647$。</li>
<li>get_c(i) 将返回 $c_i$。如果 $i$ 在 $0 \leq i &lt; n_c$ 之外，该函数将返回 $2147483647$。</li>
</ul><p>在一组测试数据中，query_kth 只会被调用一次。</p>

# 实现细节


<p>本题只支持 C/C++/Pascal。</p>
<p>你只能提交一个源文件实现如上所述的 query_kth 函数，并且遵循下面的命名和接口。</p>
<h4>C/C++</h4>
<p>你需要包含头文件 kth.h。</p>
<pre><code class="sh_cpp">int query_kth(int n_a, int n_b, int n_c, int k);</code></pre>
<p>函数 get_a, get_b, get_c 的接口信息如下。</p>
<pre><code class="sh_cpp">int get_a(int p);
int get_b(int p);
int get_c(int p);</code></pre>
<h4>Pascal</h4>
<p>你需要使用单元 graderhelperlib。</p>
<pre><code class="sh_pascal">function query_kth(n_a, n_b, n_c, k : longint) : longint;</code></pre>
<p>函数 get_a, get_b, get_c 的接口信息如下。</p>
<pre><code class="sh_pascal">function get_a(p : longint) : longint;
function get_b(p : longint) : longint;
function get_c(p : longint) : longint;</code></pre>
<p>如果有不清楚的地方，见样例及测评库下载，<strong>内附了样例程序</strong>。</p>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ol><li>第 $1$ 行: $n_a, n_b, n_c, k$</li>
<li>第 $2$ 行：$n_a$ 个整数，第 $i$ 个整数表示 $a_i$。</li>
<li>第 $3$ 行：$n_b$ 个整数，第 $i$ 个整数表示 $b_i$。</li>
<li>第 $4$ 行：$n_c$ 个整数，第 $i$ 个整数表示 $c_i$。</li>
</ol><p>在 query_k 返回后，评测系统将输出你的答案以及 get_a, get_b, get_c 三个函数的总调用次数。</p>

# 样例一


<h4>input</h4>
<pre>2 3 3 5
1 2
1 5 6
2 3 3

</pre>

<h4>output</h4>
<pre>3 6

</pre>

<h4>explanation</h4>
<p>所有激光炮从小到大排序后为 $1, 1, 2, 2, 3, 3, 5, 6$，所以第 $5$ 小的数为 $3$。输出的第二个整数 $6$ 为总调用次数，你可以认为这是一个调用了 $6$ 次 get_a, get_b, get_c 函数的程序的输出。</p>

# 样例二


<p>见样例及测评库下载。</p>

# 限制与约定


<p>共 $10$ 个测试点，每个测试点 $10$ 分。设你的程序 get_a, get_b, get_c 函数的调用次数为 $t$。当 $t \leq 100$ 时得 $10$ 分，否则当 $t \leq 2000$ 时得 $6$ 分，否则不得分。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td>$n_a, n_b, n_c \leq 30$</td>
</tr><tr><td>2</td><td rowspan="3">$n_c = 0$</td></tr><tr><td>3</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="6">无</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有测试点，$0 \leq n_a, n_b, n_c \leq 10^5$，$1 \leq a_i, b_i, c_i \leq 10^9$。</p>
<p><a href="//uoj.ac/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=52">样例及测评库下载</a></p>
