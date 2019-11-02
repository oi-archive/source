# 题目描述


# 题目描述


<p>给你一张 $n$ 个点 $m$ 条边构成的有向图 $G=(V, E)$，其中第 $i$ 条边的起点为 $from_i$，终点为 $to_i$，有容量 $cap_i$ 和费用 $cost_i$ 两个属性。并且，图中存在两个特殊点，源点 $s$ 和汇点 $t$，$s$ 点没有入边，$t$ 点没有出边。</p>
<p>定义流函数 $f:E\rightarrow N$，满足以下条件：</p>
<ol><li><p>$0\le f(i)\le cap_i$（每条边的流量不超过容量）。</p>
</li>
<li><p>$\forall u\in (V-\{s, t\}), \sum\limits_{from_i = u}f(i)=\sum\limits_{to_i = u}f(i)$（除源汇外每个点的流入量等于流出量）。</p>
</li>
</ol><p>定义一个流函数的总流量为 $s$ 流出的流量：$flow(f)=\sum_{from_i=s}f(i)$。</p>
<p>定义一个流函数的费用为每条边的流量与费用乘积之和：$cost(f)=\sum_{i\in E}f(i)cost_i$。</p>
<p>请求出最大流（$flow(f)$ 的最大值），以及最大流前提下的最小费用（在 $flow(f)$ 取到最大值的前提下 $cost(f)$ 的最小值）。</p>

# 输入格式


<p>输入的第一行包含四个正整数 $n$, $m$, $s$, $t$，分别表示图的点数和边数，源点和汇点。</p>
<p>接下来 $m$ 行中的第 $i$ 行包含四个整数 $from_i$, $to_i$, $cap_i$, $cost_i$，分别表示图中第 $i$ 条边的起点，终点，容量，费用。</p>

# 输出格式


<p>输出包含两个整数，分别表示最大流和最大流前提下的最小费用。</p>

# 样例


<h4>input</h4>
<pre><code class="sh_plain">4 5 4 3
4 2 30 2
4 3 20 3
2 3 20 1
2 1 30 9
1 3 40 5</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">50 280</code></pre>

# 限制与约定


<p>对于 $100\%$ 的数据，$1\le n, m\le 500$，$1\le s, t\le n$，$s\ne t$，$1\le from_i, to_i\le n$，$from_i\ne t$，$to_i\ne s$，$1\le cap_i\le 10^9$，$-2\cdot 10^6\le cost_i\le 2\cdot 10^6$。</p>
<p><strong>时间限制:</strong> $5s$</p>
<p><strong>空间限制:</strong> $512MB$</p>
