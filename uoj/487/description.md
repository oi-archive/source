# 题目描述

<p>给你一张 $n$ 个点 $m$ 条边构成的有向图 $G=(V, E)$，其中第 $i$ 条边的起点为 $from(i)$，终点为 $to(i)$，有容量 $cap(i)$ 和费用 $cost(i)$ 两个属性。并且，图中存在两个特殊点，源点 $s$ 和汇点 $t$，$s$ 点没有入边，$t$ 点没有出边。</p>
<p>定义流函数 $f:E\rightarrow N$ 为满足以下条件的任一函数（即 $f(i)$ 表示 $i$ 这条边的流量）：</p>
<ol><li><p>$\forall i\in E, 0\le f(i)\le cap(i)$（每条边的流量不超过容量）。</p>
</li>
<li><p>$\forall u\in (V\setminus\{s, t\}), \sum\limits_{from(i) = u\ }f(i)=\sum\limits_{to(i) = u\ }f(i)$（除源汇外每个点的流出量等于流入量）。</p>
</li>
</ol><p>定义一个流函数的流量为 $s$ 流出的流量：$flow(f)=\sum_{from(i)=s\ \ \,}f(i)$。</p>
<p>定义一个流函数的总费用为每条边的流量与费用乘积之和：$totalcost(f)=\sum_{i\in E\;}f(i)cost(i)$。</p>
<p>请求出最大流（$flow(f)$ 的最大值），以及最大流前提下的最小费用（即 $\min\{totalcost(f)|flow(f)=\max\{flow(i)|i\text{ is a flow of }G\}\}$）。</p>

# 输入格式


<p>输入的第一行包含四个正整数 $n$, $m$, $s$, $t$，分别表示图的点数和边数，源点和汇点。</p>
<p>接下来 $m$ 行中的第 $i$ 行包含四个整数 $from(i)$, $to(i)$, $cap(i)$, $cost(i)$，分别表示图中第 $i$ 条边的起点，终点，容量，费用。</p>

# 输出格式


<p>输出包含两个整数，分别表示最大流和最大流前提下的最小费用。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">4 5 4 3
4 2 30 2
4 3 20 3
2 3 20 1
2 1 30 9
1 3 40 5</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">50 280</code></pre>
<h4>explanation</h4>
<p>用 $f(u, v)$ 代指 $u$ 到 $v$ 这条边的流量，那么取到最大流前提下的最小费用时，$f(4, 2)=30$, $f(4, 3)=20$, $f(2, 3)=20$, $f(2, 1)=10$, $f(1, 3)=10$ 。</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">3 1 1 3
2 2 1 -1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">0 -1</code></pre>
<h4>explanation</h4>
<p>一个合法的流只需满足容量限制与流量平衡，一个与 $s$, $t$ 不连通的环也可以有流量。</p>

# 限制与约定


<p>对于 $100\%$ 的数据，$1\le n, m\le 500$，$1\le s, t\le n$，$s\ne t$，$1\le from(i), to(i)\le n$，$from(i)\ne t$，$to(i)\ne s$，$1\le cap(i)\le 10^9$，$-2\cdot 10^6\le cost(i)\le 2\cdot 10^6$。</p>
<p><strong>时间限制：</strong>$5\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 提示


<p>常见费用流算法的复杂度为 $O(nmf)$ (其中 $f$ 表示最大流的大小)，可能无法通过此题。</p>
<p>一种可行的解决方案是使用 <a href="https://ouuan.github.io/post/%E5%9F%BA%E4%BA%8E-capacity-scaling-%E7%9A%84%E5%BC%B1%E5%A4%9A%E9%A1%B9%E5%BC%8F%E5%A4%8D%E6%9D%82%E5%BA%A6%E6%9C%80%E5%B0%8F%E8%B4%B9%E7%94%A8%E6%B5%81%E7%AE%97%E6%B3%95/">基于 Capacity Scaling 的弱多项式复杂度最小费用流算法</a> 。</p>
