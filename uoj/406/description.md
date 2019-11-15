# 题目描述

<p>你要在一个长方形大厅里举办国际编程比赛，该大厅共有 $HW$ 个座位（$H$ 行 $W$ 列）。行的编号是从 $0$ 到 $H-1$，列的编号是从 $0$ 到 $W-1$。位于 $r$ 行 $c$ 列的座位用 $(r,c)$ 表示。一共邀请了 $HW$ 位参赛者，编号是从 $0$ 到 $HW-1$。你制定好了一个座位表，第 $i$（$0\le i\le HW-1$）个参赛者被安排到座位 $(R_i,C_i)$。座位表中参赛者和座位是一一对应的。</p>
<p>大厅中一个座位集合 $S$ 被称为是长方形的，如果存在整数 $r_1,r_2,c_1$ 和 $c_2$ 满足下列条件：</p>
<ul><li>$0\le r_1\le r_2\le H-1$。</li>
<li>$0\le c_1\le c_2\le W-1$。</li>
<li>$S$ 正好是所有满足 $r_1\le r\le r_2$ 和 $c_1\le c\le c_2$ 的座位 $(r,c)$ 的集合。</li>
</ul><p>如果一个长方形座位集合包含 $k$（$1\le k\le HW$）个座位，并且被分配到这个集合的参赛者的编号恰好是从 $0$ 到 $k-1$，那么该集合是<strong>美妙的</strong>。一个座位表的<strong>美妙度</strong>定义为这个表中美妙的长方形座位集合的个数。</p>
<p>在准备好座位表后，你会收到一些交换两个参赛者座位的请求。具体来说，有 $Q$ 个这样的请求，按时间顺序编号为 $0$ 到 $Q-1$。第 $j$（$0\le j\le Q-1$）个请求希望交换参赛者 $A_j$ 和 $B_j$ 的座位。你立即接受每个请求并更新座位表。每次更新后，你的目标是计算当前座位表的美妙度。</p>

# 实现细节


<p>你应该实现下列过程和函数：</p>
<pre><code class="sh_cpp">give_initial_chart(int H, int W, int[] R, int[] C)</code></pre>
<ul><li><code>H</code>, <code>W</code>：行数和列数</li>
<li><code>R</code>, <code>C</code>：两个长度为 $HW$ 的数组，代表初始的座位表</li>
<li>这个过程只被调用一次，而且是在 <code>swap_seats</code> 的任何调用之前。</li>
</ul><pre><code class="sh_cpp">int swap_seats(int a, int b)</code></pre>
<ul><li>该函数用来处理一次交换座位的请求</li>
<li><code>a</code>, <code>b</code>：需要交换座位的参赛者</li>
<li>该函数被调用 $Q$ 次</li>
<li>该函数应返回交换座位后座位表的美妙度</li>
</ul>
# 例子


<p>令 $H=2$，$W=3$，$R=[0,1,1,0,0,1]$，$C=[0,0,1,1,2,2]$，和 $Q=2$。</p>
<p>评测程序先调用 <code>give_initial_chart(2, 3, [0, 1, 1, 0, 0, 1], [0, 0, 1, 1, 2, 2])</code>。</p>
<p>最初，座位表如下：</p>
<p>\begin{matrix}
0 &amp; 3 &amp; 4 \\
1 &amp; 2 &amp; 5
\end{matrix}</p>
<p>假设评测程序调用 <code>swap_seats(0, 5)</code>。在这个编号为 $0$ 的请求完成后，座位表变成：</p>
<p>\begin{matrix}
5 &amp; 3 &amp; 4 \\
1 &amp; 2 &amp; 0
\end{matrix}</p>
<p>对应参赛者集合 $\{0\},\{0,1,2\}$ 和 $\{0,1,2,3,4,5\}$ 的三个座位集合都是长方形和美妙的。所以，该座位表的美妙度为 $3$，<code>swap_seats</code> 应该返回 $3$。</p>
<p>假设评测程序再次调用 <code>swap_seats(0, 5)</code>。在这个编号为 $1$ 的请求完成后，座位表回到初始状态。对应参赛者集合 $\{0\},\{0,1\},\{0,1,2,3\}$ 和 $\{0,1,2,3,4,5\}$ 的四个座位集合都是长方形和美妙的。所以，该表的美妙度为 $4$，<code>swap_seats</code> 应该返回 $4$。</p>
<p>在样例数据下载中的文件<code>ex_seats1.in</code>和<code>ex_seats1.out</code>对应于上述例子。此外，样例数据包中还有一些其他的输入输出例子。</p>

# 限制条件


<ul><li>$1\le H$</li>
<li>$1\le W$</li>
<li>$HW\le 1\ 000\ 000$</li>
<li>$0\le R_i\le H-1$（$0\le i\le HW-1$）</li>
<li>$0\le C_i\le W-1$（$0\le i\le HW-1$）</li>
<li>$(R_i,C_i)\ne(R_j,C_j)$（$0\le i&lt;j\le HW-1$）</li>
<li>$1\le Q\le 50\ 000$</li>
<li>对于 <code>swap_seats</code> 的所有调用，$0\le a\le HW-1$</li>
<li>对于 <code>swap_seats</code> 的所有调用，$0\le b\le HW-1$</li>
<li>对于 <code>swap_seats</code> 的所有调用，$a\ne b$</li>
</ul>
# 子任务


<ol><li>（5分）$HW\le 100$，$Q\le 5\ 000$</li>
<li>（6分）$HW\le 10\ 000$，$Q\le 5\ 000$</li>
<li>（20分）$H\le 1\ 000$，$W\le 1\ 000$，$Q\le 5\ 000$</li>
<li>（6分） 对于 <code>swap_seats</code> 的所有调用，$Q\le 5\ 000$，$|a-b|\le 10\ 000$ </li>
<li>（33分）$H=1$</li>
<li>（30分）无附加限制条件</li>
</ol>
# 评测程序示例


<p>评测程序示例按照以下格式读入输入</p>
<ul><li>第 $1$ 行：$H\ W\ Q$</li>
<li>第 $2+i$ 行（$0\le i\le HW-1$） : $R_i\ C_i$</li>
<li>第 $2+HW+j$ 行（$0\le j\le Q-1$）：$A_j\ B_j$</li>
</ul><p>这里 $A_j$ 和 $B_j$ 是调用 <code>swap_seats</code> 处理请求时的参数。</p>
<p>评测程序示例按照以下格式打印你的答案：</p>
<ul><li>第 $1+j$ 行（$0\le j\le Q-1$）：<code>swap_seats</code> 对于请求 $j$ 的返回值</li>
</ul>
# 约定及限制


<p>对于所支持的各种编程语言，下面列出了对应的数据类型。对于数据类型的细节等，参见实现示例。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>语言</th>
<th>$\texttt{int}$</th>
<th>$\texttt{int64}$</th>
<th>$\texttt{int[]}$</th>
<th>数组$a$的长度</th>
<th>$\texttt{string}$</th>
</tr></thead><tbody><tr><td>$\texttt{C++}$</td><td>$\texttt{int}$</td><td>$\texttt{long long}$</td><td>$\texttt{std::vector&lt;int&gt;}$</td><td>$\texttt{a.size()}$</td><td>$\texttt{std::string}$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$268\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=406">样例数据下载</a></p>
