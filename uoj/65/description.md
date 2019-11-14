# 题目描述

<p>有一天，VFleaKing到森林里游玩，回来之后跟pyx1997说，我发现好多棵会动的树耶！pyx1997说，这有什么好稀奇的，我用手指头就能维护每棵树的形态。</p>
<p>于是又过了几天VFleaKing到沙漠里游玩，回来之后跟pyx1997说，我发现好多棵会动的仙人掌耶！pyx1997说，这有什么好稀奇的，我用脚丫子就能维护每棵仙人掌的形态。</p>
<p>于是VFleaKing很郁闷，他向你求助，请帮帮他吧。</p>
<p>如果一个无向连通图的任意一条边最多属于一个简单环，我们就称之为仙人掌。</p>
<p>如果一个无向图的每个连通块都是个仙人掌，且不存在自环，我们就称之为沙漠。</p>
<p>为了证明你确实能够维护仙人掌，我们给你 $n$ 个结点，从 $1$ 到 $n$ 标号。初始时没有任何边。每次进行如下操作之一：</p>
<ol><li>link $v$ $u$ $w_a$ $w_b$：在结点 $v, u$ 间连一条权值A为 $w_a$、权值B为 $w_b$ 的边。<ul><li>$1 \leq v, u \leq n$ 且 $w_a, w_b$ 为正整数。</li>
<li>如果连边完成后图仍为沙漠，则输出 &#34;<samp>ok</samp>&#34;（不含引号）。</li>
<li>否则操作非法，撤销此次操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
<li>cut $v$ $u$ $w_a$ $w_b$：在结点 $v, u$ 间删掉一条权值A为 $w_a$、权值B为 $w_b$ 的边。<ul><li>$1 \leq v, u \leq n$ 且 $w_a, w_b$ 为正整数。</li>
<li>如果存在这样的边则输出 &#34;<samp>ok</samp>&#34;（不含引号）（如果有多条权值A为 $w_a$、权值B为 $w_b$ 的边删去任意一条）。</li>
<li>否则操作非法，不进行操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
<li>distance? $v$ $u$：查询结点 $v$ 到结点 $u$ 的按权值A计算的最短路信息。<ul><li>$1 \leq v, u \leq n$。</li>
<li>输出两个用空格隔开的整数 $l_m, w_m$。</li>
<li>$l_m$ 代表按权值A计算的最短路的长度，$w_m$代表最短路上的边的权值B的最小值。</li>
<li>如果 $v = u$ 则 $l_m = 0, w_m = 2147483647$。</li>
<li>如果没有路可到达则 $l_m = -1, w_m = -1$。</li>
<li>如果最短路不唯一则 $w_m = -1$。</li>
</ul></li>
<li>add $v$ $u$ $d$：把结点 $v$ 到结点 $u$ 的按权值A计算的最短路上的每一条边的权值B都加上 $d$。<ul><li>$1 \leq v, u \leq n$, $v \neq u$ 且 $d$ 为正整数。</li>
<li>如果有路可到达且最短路唯一，则输出 &#34;<samp>ok</samp>&#34;（不含引号）</li>
<li>否则操作非法，不进行操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
</ol>
# 输入格式


<p>第一行两个用空格隔开的正整数 $n, m$ 表示一共有 $n$ 个结点，$m$ 个操作。</p>
<p>接下来 $m$ 行，每行代表一个操作。</p>

# 输出格式


<p>对于每个操作，输出相应的结果。</p>

# 样例一


<h4>input</h4>
<pre>6 56
link 1 2 1 3
link 1 2 2 5
distance? 1 2
cut 1 2 1 3
link 1 2 2 5
distance? 1 2
cut 1 2 2 5
link 1 2 2 4
add 1 2 1
cut 1 2 2 4
cut 1 2 2 5
link 3 3 2 2
cut 4 4 2 2
link 1 2 2 4
link 1 3 3 5
link 2 3 4 3
distance? 1 2
distance? 1 3
distance? 2 4
add 1 2 3
link 2 4 3 2
link 3 5 3 4
link 4 5 1 5
distance? 4 5
cut 1 2 2 7
link 4 5 5 4
distance? 1 5
cut 2 3 4 3
link 2 5 5 3
link 1 5 2 4
distance? 1 2
add 3 4 3
cut 4 5 5 7
distance? 1 2
cut 3 5 3 7
distance? 1 2
cut 2 5 5 4
cut 2 5 5 3
distance? 1 2
add 1 2 3
link 3 5 6 7
distance? 1 3
add 3 5 1
distance? 5 3
distance? 4 3
link 4 6 3 1
link 2 6 7 2
distance? 2 6
link 5 6 2 4
distance? 1 6
distance? 2 3
cut 2 4 3 2
link 2 5 4 3
distance? 4 1
cut 4 6 3 1
distance? 4 1

</pre>

<h4>output</h4>
<pre>ok
ok
1 3
ok
ok
2 -1
ok
ok
failed
ok
ok
failed
failed
ok
ok
ok
2 4
3 5
-1 -1
ok
ok
ok
failed
10 2
ok
ok
6 4
ok
ok
ok
7 3
ok
ok
7 3
ok
7 3
failed
ok
-1 -1
failed
ok
3 5
ok
5 5
-1 -1
ok
ok
6 1
ok
4 4
13 1
ok
ok
7 1
ok
-1 -1

</pre>


# 限制与约定


<p>$1 \leq n \leq 100000, 1 \leq m \leq 500000$。</p>
<p>保证 link 和 cut 操作中的 $w_a$ 满足 $1 \leq w_a \leq 10000$，$1 \leq w_b \leq 10^9$，且 add 操作中的 $d$ 之和不超过 $10^9$。所以关于边权的计算不会超出 32 位有符号整数范围。</p>
<p><strong>时间限制：</strong>$5\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=65">样例数据下载</a></p>
