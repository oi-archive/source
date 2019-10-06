# 题目描述

<p>为了庆祝 NOI 的成功开幕，主办方为大家准备了一场寿司晚宴。小 G 和小 W 作为参加 NOI 的选手，也被邀请参加了寿司晚宴。</p>
<p>在晚宴上，主办方为大家提供了 $n − 1$ 种不同的寿司，编号 $1, 2, 3, \dots, n − 1$，其中第 $i$ 种寿司的美味度为 $i + 1$ （即寿司的美味度为从 $2$ 到 $n$）。</p>
<p>现在小 G 和小 W 希望每人选一些寿司种类来品尝，他们规定一种品尝方案为不和谐的当且仅当：小 G 品尝的寿司种类中存在一种美味度为 $x$ 的寿司，小 W 品尝的寿司中存在一种美味度为 $y$ 的寿司，而 $x$ 与 $y$ 不互质。</p>
<p>现在小 G 和小 W 希望统计一共有多少种和谐的品尝寿司的方案（对给定的正整数 $p$ 取模）。注意一个人可以不吃任何寿司。</p>

# 输入格式


<p>输入文件的第 $1$ 行包含 $2$ 个正整数 $n, p$，中间用单个空格隔开，表示共有 $n$ 种寿司，最终和谐的方案数要对 $p$ 取模。</p>

# 输出格式


<p>输出一行包含 $1$ 个整数，表示所求的方案模 $p$ 的结果。</p>

# 样例一


<h4>input</h4>
<pre>3 10000

</pre>

<h4>output</h4>
<pre>9

</pre>


# 样例二


<h4>input</h4>
<pre>4 10000

</pre>

<h4>output</h4>
<pre>21

</pre>


# 样例三


<h4>input</h4>
<pre>100 100000000

</pre>

<h4>output</h4>
<pre>3107203

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$ 的规模</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$2 \leq n \leq 30$</td><td rowspan="10">$0 &lt; p \leq 1000000000$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">$2 \leq n \leq 100$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="2">$2 \leq n \leq 200$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$2 \leq n \leq 500$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=129">样例数据下载</a></p>
