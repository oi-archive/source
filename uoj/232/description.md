# 题目描述

<p>像他的祖先一样，Mansur 喜欢繁殖马匹。目前，他拥有哈萨克斯坦最大的马场。以前情况可不是这样，$N$ 年前 Mansur 年轻时，他只拥有一匹马，但他一直梦想着成为富豪，最终，他美梦成真。</p>
<p>按照时间的先后顺序将年份编号为 $0$ 到 $N - 1$（即 $N - 1$ 年是最近的一年）。每年的天气会影响马匹的繁殖。Mansur 用一个正整数 $X[i]$ 记录第 $i$ 年的繁殖系数，如果第 $i$ 年开始时有 $h$ 匹马，那么这一年结束时有 $h \cdot X[i]$ 匹马。</p>
<p>每年，只有年底的时候可以出售⻢匹。Mansur ⽤⼀个正整数 $Y[i]$ 记录第 $i$ 年末卖出⼀匹⻢的售价。Mansur 可以卖出任意多匹⻢，每匹售价均为 $Y[i]$。</p>
<p>现在，Mansur 想知道如果在 $N$ 年中，他总能在最佳时间出售⻢匹，他能获得的最⼤收益是多少？你正好在 Mansur 家做客，所以他想请你帮他回答这个问题。</p>
<p>Mansur 对记录下的 $X$ 和 $Y$ 做了 $M$ 次更新，每次更新，Mansur 要么改变⼀个 $X[i]$，要么改变⼀个 $Y[i]$。每次更新后，他都会问你出售⻢匹能获得的最⼤收益。Mansur 的更新是累加的，即你的每个回答时都应该考虑之前的所有更新。注意：某个 $X[i]$ 或者 $Y[i]$ 可能会被更新多次。</p>
<p>对于 Mansur 的问题，实际的答案可能是⼀个⾮常⼤的数字，你只要给出实际答案模 $10^9 + 7$ 后的结果即可。</p>
<p>设 $N = 3$，$X$ 和 $Y$ 如下所⽰：</p>
<div class="row">
<div class="col-sm-offset-4 col-sm-4">
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th></th>
<th>0</th>
<th>1</th>
<th>2</th>
</tr></thead><tbody><tr><td>X</td><td>2</td><td>1</td><td>3</td></tr><tr><td>Y</td><td>3</td><td>4</td><td>1</td></tr></tbody></table></div>
</div>
</div>

<p>上述情况下，Mansur 在 1 年末卖掉他的⻢可以获得最⼤收益。具体说明如下：</p>
<ul><li>起初，Mansur 有 1 匹⻢。</li>
<li>0 年末，他有 $1 \cdot X[0] = 2$ 匹⻢。</li>
<li>1 年末，他有 $2 \cdot X[1] = 2$ 匹⻢。</li>
<li>1 年末，他卖掉 2 匹⻢，总收益是 $2 \cdot Y[1] = 8$。</li>
</ul><p>然后，设 $M = 1$：将 $Y[1]$ 更新为 $2$，更新后的信息如下：</p>
<div class="row">
<div class="col-sm-offset-4 col-sm-4">
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th></th>
<th>0</th>
<th>1</th>
<th>2</th>
</tr></thead><tbody><tr><td>X</td><td>2</td><td>1</td><td>3</td></tr><tr><td>Y</td><td>3</td><td>2</td><td>1</td></tr></tbody></table></div>
</div>
</div>

<p>这种情况下，⼀种获得最⼤收益的⽅案是 0 年末卖掉 $1$ 匹⻢，然后 2 年末卖掉 $3$ 匹⻢。整个过程说明如下：</p>
<ul><li>起初，Mansur 有1匹⻢。</li>
<li>0 年末，他有 $1 \cdot X[0] = 2$ 匹⻢。</li>
<li>0 年末，他卖掉 1 匹⻢，获益 $Y[0] = 3$，于是他只剩下 1 匹⻢。</li>
<li>1 年末，他有 $1 \cdot X[1] = 1$ 匹⻢。</li>
<li>2 年末，他有 $1 \cdot X[2] = 3$ 匹⻢。</li>
<li>2 年末，他卖掉 3 匹⻢，获益 $3 \cdot Y[2] = 3$，总收益是 $3 + 3 = 6$。</li>
</ul>
# 任务


<p>给定 $N, X, Y$ 和⼀系列更新操作。第⼀次更新前和每次更新后，计算 Mansur 可以获得的最⼤收益（注意：给出实际最⼤收益模 $10^9 + 7$ 后的结果）。你需要实现函数 init, updateX 和 updateY。</p>
<ul><li>init(N, X, Y) — grader⾸先调⽤此函数恰好⼀次。<ul><li>N: 表⽰总共有 $N$ 年。</li>
<li>X: ⻓度为 $N$ 的数组，对 $0 \le i \le N - 1$，$X[i]$ 表⽰ $i$ 年的繁殖系数。</li>
<li>Y: ⻓度为 $N$ 的数组，对 $0 \le i \le N - 1$，$Y[i]$ 表⽰ $i$ 年末出售⼀匹⻢的价格。</li>
<li>注意：X、Y均为Mansur给定的初值（更新前的值）。</li>
<li>init 函数结束后，数组 X 和 Y 仍然有效，你可以随意修改这两个数组的内容。</li>
<li>该函数返回初始状态下，Mansur 获得的最⼤收益模 $10^9 + 7$ 后的值。</li>
</ul></li>
<li>updateX(pos, val)<ul><li>pos: ⼀个整数，范围是 $0, \ldots, N - 1$。</li>
<li>val: $X[pos]$ 更新后的值。</li>
<li>该函数返回这次更新后Mansur获得的最⼤收益模 $10^9 + 7$ 的值。</li>
</ul></li>
<li>updateY(pos, val)<ul><li>pos: ⼀个整数，范围是 $0, \ldots, N - 1$。</li>
<li>val: $Y[pos]$ 更新后的值。</li>
<li>该函数返回这次更新后Mansur获得的最⼤收益模 $10^9 + 7$ 的值。</li>
</ul></li>
</ul><p>$X[i]$、$Y[i]$ 的初值以及更新后值范围均为 $[1, 10^9]$。
调⽤ init 后，grader 会调⽤ updateX 和 updateY 若⼲次，调⽤ updateX 和 updateY 的总次数是 $M$。</p>

# 子任务


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$N$</th>
<th>$M$</th>
<th>限制</th>
</tr></thead><tbody><tr><td>1</td><td>17</td><td>$1 \leq N \leq 10$</td><td>$M = 0$</td><td>$X[i], Y[i] \le 10, X[0] \cdot X[1] \cdot \cdots \cdot X[N - 1] \le 1000$</td></tr><tr><td>2</td><td>17</td><td>$1 \le N \le 1000$</td><td>$0 \le M \le 1000$</td><td>无</td></tr><tr><td>3</td><td>20</td><td>$1 \leq N \leq 500000$</td><td>$0 \le M \le 100000$</td><td>调用 init 时的 $X[i] \ge 2$, 且 updateX 调用时的 $val \ge 2$</td></tr><tr><td>4</td><td>23</td><td>$1 \leq N \leq 500000$</td><td>$0 \le M \le 10000$</td><td>无</td></tr><tr><td>5</td><td>23</td><td>$1 \leq N \leq 500000$</td><td>$0 \leq M \leq 100000$</td><td>无</td></tr></tbody></table></div>



# 实现细节


<p>你只能提交一个源文件实现如上所述的 init, updateX和updateY 函数，并且遵循下面的命名和接口。你需要包含头文件 horses.h。</p>
<pre><code class="sh_cpp">int init(int N, int X[], int Y[]);
int updateX(int pos, int val);
int updateY(int pos, int val);</code></pre>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ul><li>第 $1$ 行：$N$</li>
<li>第 $2$ 行：$X[0] \ldots X[N-1]$</li>
<li>第 $3$ 行：$Y[0] \ldots Y[N-1]$</li>
<li>第 $4$ 行：$M$</li>
<li>第 $5， \ldots, M + 4$ 行：每行 $3$ 个数字 type pos val（type = 1 表示 updateX，type = 2 表示 updateY）</li>
</ul><p>评测系统将打印 init 的返回值，以及所有调⽤ updateX 和 updateY 后的返回值。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=232">样例及测评库下载</a></p>
