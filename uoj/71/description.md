# 题目描述

<p>给出一个有向带权网络 $G = (V, E)$，权值函数 $w: E \rightarrow \mathbb{Z^{*}}$（即任意边 $e$ 的权值 $w(e)$ 均为正整数），和点 $s, t \in E$，使得在 $G&#39; = (V, E - S)$ 上不存在 $s$ 到 $t$ 的路径。</p>
<p>设 $\mathfrak{S}$ 是所有满足条件的边集 $S$ 的全集，按 $w(S)$  从小到大输出 $\mathfrak{S}$ 中前 $k$ 小的边集的边权和。其中 $w(S) = \sum_{e \in S} w(e)$。</p>

# 输入格式


<p>第一行包含 $5$ 个正整数 $n, m, s, t, k$，其中 $s, t, k$ 意义如上，$n, m$ 分别表示 $\lvert V \rvert, \lvert E \rvert$（即点数和边数）。规定图中的节点用 $1$ 到 $n$ 的整数表示。保证 $s \neq t$。</p>
<p>接下来 $m$ 行，每行 $3$ 个整数 $x, y, z$，表示一条边权为 $z$ 的从 $x$ 到 $y$ 的边。可能有重边但保证没有自环。</p>

# 输出格式


<p>如果 $\lvert \mathfrak{S} \rvert &lt; k$，先输出 $\lvert \mathfrak{S} \rvert$ 行，每行包含一个整数，表示前 $\lvert \mathfrak{S} \rvert$ 个 $w(S)$；再输出一行一个整数 $-1$。</p>
<p>如果 $\lvert \mathfrak{S} \rvert \geq k$，则输出 $k$ 行，表示前 $k$ 个 $w(S)$。</p>
<p>两种情况均需按照 $w(S)$ 从小到大输出。</p>

# 样例一


<h4>input</h4>
<pre>3 3 1 3 100
1 2 3
2 3 4
1 3 5

</pre>

<h4>output</h4>
<pre>8
9
12
-1

</pre>


# 样例二


<h4>input</h4>
<pre>5 8 1 5 10
1 2 45176
1 3 41088
1 4 32001
2 5 48931
3 5 39291
4 5 28970
2 3 48131
4 2 49795

</pre>

<h4>output</h4>
<pre>116468
117192
118265
120223
145438
147235
149193
157556
158280
161311

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$k$</th>
<th>约束</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$\leq 10$</td><td rowspan="2">$\leq 20$</td><td rowspan="2">$\leq 1000000$</td><td rowspan="6">边权不超过 $65536$</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="4">$\leq 50$</td><td rowspan="4">$\leq 100$</td><td rowspan="4">$\leq 100$</td></tr><tr><td>4</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$\leq 3000$</td><td rowspan="8">$= 2n - 4$</td><td rowspan="4">$\leq 500000$</td><td rowspan="8">$s$ 有边连向所有非 $t$ 节点，<br/> 所有非 $s$ 结点有边连向 $t$，<br/> 边权不超过 $2^{31} - 1$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr><tr><td>11</td><td rowspan="4">$\leq 150000$</td><td rowspan="4">$\leq 500000$</td></tr><tr><td>12</td></tr><tr><td>13</td></tr><tr><td>14</td></tr><tr><td>15</td><td rowspan="6">$\leq 50$</td><td rowspan="6">$\leq 1500$</td><td rowspan="6">$\leq 100$</td><td rowspan="6">边权不超过 $65536$</td></tr><tr><td>16</td></tr><tr><td>17</td></tr><tr><td>18</td></tr><tr><td>19</td></tr><tr><td>20</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=71">样例数据下载</a></p>
