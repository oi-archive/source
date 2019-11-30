# 题目描述

<p>有一天，wangyisong1996到森林里游玩，回来之后跟VFleaKing说，我发现好多棵会动的树耶！VFleaKing说，这有什么好稀奇的，我用手指头就能维护每棵树的形态。</p>
<p>于是又过了几天wangyisong1996到沙漠里游玩，回来之后跟VFleaKing说，我发现好多棵会动的仙人掌耶！VFleaKing说，这有什么好稀奇的，我用脚丫子就能维护每棵仙人掌的形态。</p>
<p>于是wangyisong1996很郁闷，他向你求助，请帮帮他吧。</p>
<p>如果一个无向连通图的任意一条边最多属于一个简单环，我们就称之为仙人掌。</p>
<p>如果一个无向图的每个连通块都是个仙人掌，且不存在自环，我们就称之为沙漠。</p>
<p>为了证明你确实能够维护仙人掌，我们给你 $n$ 个结点，从 $1$ 到 $n$ 标号。</p>
<p>初始时没有任何边，且每个结点 $i$ 有个权值 $w_i$ $(w_i &gt; 0)$ 。每次进行如下操作之一：</p>
<ol><li>link $v$ $u$ $w$：在结点 $v, u$ 间连一条权值为 $w$ 的边。<ul><li>$1 \leq v, u \leq n$ 且 $w$ 为正整数。</li>
<li>如果连边完成后图仍为沙漠，则输出 &#34;<samp>ok</samp>&#34;（不含引号）。</li>
<li>否则操作非法，撤销此次操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
<li>cut $v$ $u$ $w$：在结点 $v, u$ 间删掉一条权值为 $w$ 的边。<ul><li>$1 \leq v, u \leq n$ 且 $w$ 为正整数。</li>
<li>如果存在这样的边则输出 &#34;<samp>ok</samp>&#34;（不含引号）（如果有多条权值为 $w$ 的边删去任意一条）。</li>
<li>否则操作非法，不进行操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
<li>query1 $v$ $u$：查询结点 $v$ 到结点 $u$ 的最短路信息。<ul><li>$1 \leq v, u \leq n$。</li>
<li>输出两个用空格隔开的整数 $\min, \sigma$，分别代表最短路上点权的最小值、和。</li>
<li>如果没有路可到达则 $\min = -1, \sigma = -1$。</li>
<li>如果最短路不唯一则 $\min = -2, \sigma = -2$。</li>
</ul></li>
<li>query2 $v$ $u$：查询以结点 $v$ 为根，子仙人掌 $u$ 的信息。<ul><li>$1 \leq v, u \leq n$。</li>
<li>以结点 $v$ 为根，子仙人掌 $u$ 的定义是，删掉 $v$ 到 $u$ 之间的所有简单路径上的边之后，$u$ 所在的连通块。</li>
<li>输出两个用空格隔开的整数 $\min, \sigma$，分别代表子仙人掌 $u$ 中点权的最小值、和。</li>
<li>如果 $v, u$ 不连通则 $\min = -1, \sigma = -1$。</li>
</ul></li>
<li>add1 $v$ $u$ $d$：把结点 $v$ 到结点 $u$ 的最短路上的每一个结点的权值都加上 $d$。<ul><li>$1 \leq v, u \leq n$ 且 $d$ 为正整数。</li>
<li>如果有路可到达且最短路唯一，则输出 &#34;<samp>ok</samp>&#34;（不含引号）</li>
<li>否则操作非法，不进行操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
<li>add2 $v$ $u$ $d$：把以结点 $v$ 为根，子仙人掌 $u$ 的每一个结点的权值都加上 $d$。<ul><li>$1 \leq v, u \leq n$ 且 $d$ 为正整数。</li>
<li>如果 $v, u$ 在同一个连通块里，则输出 &#34;<samp>ok</samp>&#34;（不含引号）</li>
<li>否则操作非法，不进行操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
</ol>
# 输入格式


<p>第一行两个用空格隔开的正整数 $n, m$ 表示一共有 $n$ 个结点，$m$ 个操作。</p>
<p>接下来一行 $n$ 个正整数，第 $i$ 个正整数为 $w_i$。</p>
<p>接下来 $m$ 行，每行代表一个操作。</p>

# 输出格式


<p>对于每个操作，输出相应的结果。</p>

# 样例一


<h4>input</h4>
<pre>11 23
10 5 11 7 8 14 30 3 16 20 19
link 1 2 5
link 2 3 3
link 3 4 7
link 4 5 8
link 2 6 10
link 6 7 15
link 4 7 3
link 6 8 9
link 6 8 6
link 7 9 12
link 9 11 10
link 7 10 4
link 9 10 8
query1 6 11
query1 2 10
query2 8 7
add1 8 5 100
query1 1 7
query2 8 7
add2 11 7 1000
query1 8 3
add2 3 2 2333
query1 1 5

</pre>

<h4>output</h4>
<pre>ok
ok
ok
ok
ok
ok
ok
ok
ok
ok
ok
ok
ok
-2 -2
5 73
16 85
ok
5 263
16 185
ok
1005 4233
ok
1011 9907

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>$1 \leq n \leq 50000, 1 \leq m \leq 250000$。</p>
<p>保证 link 和 cut 操作中的 $w$ 满足 $1 \leq w \leq 10000$，所以关于边权的计算不会超出 32 位有符号整数范围。</p>
<p>保证初始的 $w_i$ 不超过 $10^9$，保证所有 add1 和 add2 操作中的 $d$ 之和不超过 $10^9$。</p>
<p><strong>时间限制：</strong>$6\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=106">样例数据下载</a></p>
