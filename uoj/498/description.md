# 题目描述

<p>杰瑞正在被汤姆追捕！</p>
<p>为了摆脱追捕，杰瑞需要知道有地图有多少个老鼠洞可以隐藏！</p>
<p>但两只鞋太太的家实在太大了，为了简单地说明，定义两个简单无向图 $G_{1} =( V_{1} ,E_{1}) ,G_{2} =( V_{2} ,E_{2})$ 的乘积为一个新的图 $G_{1} \times G_{2} =\left( V^{*} ,E^{*} \right)$。</p>
<p>其中新的点集 $V^{*}$ 为:</p>
<p>$$
V^{*} = \left\{{(a,b)| a \in V_{1}, b \in V_{2}}\right\}
$$</p>
<p>其中新的边集 $E^{*}$ 为：</p>
<p>$$
E^{*} =\left\{\left(( u_{1} ,v_{1}) ,( u_{2} ,v_{2})\right) \mid ( u_{1} ,u_{2}) \in E_{1}, ( v_{1} ,v_{2}) \in E_{2}\right\}
$$</p>
<p>对于正整数 $n$，以及给定的图 $G_{1} ,G_{2} ,\dotsc ,G_{n}$，两只鞋太太的家可以表示成</p>
<p>$$
H = (((G_1 \times G_2) \times G_3) \times \cdots) \times G_n
$$</p>
<p>为了方便逃亡（戏弄汤姆），对于同一个连通块，杰瑞事先打通了所有的老鼠洞，你只需要计算一遍。</p>
<p>为了方便逃亡（戏弄汤姆），对于同一个任何一个连通块，都有老鼠洞。</p>
<p>也就是说，你需要求的是 $H$ 的连通块数量。但是杰瑞忘记了每个 $G_k$ 的具体细节，所以我们现在假设每个 $G_k$ 中任意两点间都有 $\frac12$ 的概率连边，求 $H$ 的连通块的期望。显然 $G_k$ 的全体取法共有 ${\large {2^{\binom{m_1}2 + \binom{m_2}2 + \cdots + \binom{m_n}2}}}$ 种。</p>
<p>方便起见，你只需要输出答案乘以 ${\large {2^{\binom{m_1}2 + \binom{m_2}2 + \cdots + \binom{m_n}2}}}$，对 $998244353$ 取模即可。</p>

# 输入格式


<p>第一行输入一个正整数 $n$。</p>
<p>接下来一行输入 $n$ 个正整数,第 $k$ 个正整数为 $m_k$，表示第 $k$ 个图的顶点数量。</p>

# 输出格式


<p>输出一个整数，表示答案 $\bmod 998244353$。</p>

# 样例一


<h4>input</h4>
<pre>1
3

</pre>

<h4>output</h4>
<pre>13

</pre>

<h4>explanation</h4>
<p>注意对于 $n=1$ 的情况，就是枚举所有节点个数为$m_1$的带标号无向图的连通块数量之和。</p>

# 样例二


<h4>input</h4>
<pre>2
2 3

</pre>

<h4>output</h4>
<pre>73

</pre>

<h4>explanation</h4>
<p>$G_1$ 中有 $0$ 条边的情况下，任何一种 $G_2$ 都会导致 $H$ 中有 $6$ 个连通块，这样的方案共有 $8$ 种。</p>
<p>$G_1$ 中有 $1$ 条边，$G_2$ 中有 $0$ 条边的情况下，$H$ 中有 $6$ 个连通块，这样的方案有 $1$ 种。</p>
<p>$G_1$ 中有 $1$ 条边，$G_2$ 中有 $1$ 条边的情况下，$H$ 中有 $4$ 个连通块，这样的方案有 $3$ 种。</p>
<p>$G_1$ 中有 $1$ 条边，$G_2$ 中有 $2$ 条边的情况下，$H$ 中有 $2$ 个连通块，这样的方案有 $3$ 种。</p>
<p>$G_1$ 中有 $1$ 条边，$G_2$ 中有 $3$ 条边的情况下，$H$ 中有 $1$ 个连通块，这样的方案有 $1$ 种。
$$
6\times 8 + 6\times 1 + 4\times 3 + 2\times 3 + 1\times 1 = 73
$$</p>

# 样例三


<h4>input</h4>
<pre>2
4 4

</pre>

<h4>output</h4>
<pre>21565

</pre>


# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m_k$</th></tr></thead><tbody><tr><td>$1$</td><td rowspan="1">$\le 4$</td><td rowspan="1">$\le 4$</td></tr><tr><td>$2$</td><td rowspan="1">$ = 1$</td><td rowspan="1">$\le 10^3$</td></tr><tr><td>$3$</td><td rowspan="1">$ = 1$</td><td rowspan="1">$\le 10^5$</td></tr><tr><td>$4$</td><td rowspan="1">$ = 2$</td><td rowspan="1">$\le 10^3$</td></tr><tr><td>$5$</td><td rowspan="1">$ = 2$</td><td rowspan="1">$\le 10^5$</td></tr><tr><td>$6$</td><td rowspan="1">$\le 10^3$</td><td rowspan="1">$\le 10^3$</td></tr><tr><td>$7$</td><td rowspan="1">$\le 10^5$</td><td rowspan="1">$\le 10^3$</td></tr><tr><td>$8$</td><td rowspan="1">$\le 10^5$</td><td rowspan="1">$\le 10^5$</td></tr><tr><td>$9$</td><td rowspan="1">$\le 10^5$</td><td rowspan="1">$\le 10^5$</td></tr><tr><td>$10$</td><td rowspan="1">$\le 10^5$</td><td rowspan="1">$\le 10^5$</td></tr></tbody></table></div>

<p>对于所有测试数据，满足 $1\le n, m_k\le 10^5$。</p>
<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=498">样例数据下载</a></p>
