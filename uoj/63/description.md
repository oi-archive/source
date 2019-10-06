# 题目描述

<p>有一天，VFleaKing到森林里游玩，回来之后跟pyx1997说，我发现好多棵会动的树耶！pyx1997说，这有什么好稀奇的，我用手指头就能维护每棵树的形态。</p>
<p>于是又过了几天VFleaKing到沙漠里游玩，回来之后跟pyx1997说，我发现好多棵会动的仙人掌耶！pyx1997说，这有什么好稀奇的，我用脚丫子就能维护每棵仙人掌的形态。</p>
<p>于是VFleaKing很郁闷，他向你求助，请帮帮他吧。</p>
<p>如果一个无向连通图的任意一条边最多属于一个简单环，我们就称之为仙人掌。</p>
<p>如果一个无向图的每个连通块都是个仙人掌，且不存在自环，我们就称之为沙漠。</p>
<p>为了证明你确实能够维护仙人掌，我们给你 $n$ 个结点，从 $1$ 到 $n$ 标号。初始时没有任何边。每次进行如下操作之一：</p>
<ol><li>link $v$ $u$ $w$：在结点 $v, u$ 间连一条权值为 $w$ 的边。<ul><li>$1 \leq v, u \leq n$ 且 $w$ 为正整数。</li>
<li>如果连边完成后图仍为沙漠，则输出 &#34;<samp>ok</samp>&#34;（不含引号）。</li>
<li>否则操作非法，撤销此次操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
<li>cut $v$ $u$ $w$：在结点 $v, u$ 间删掉一条权值为 $w$ 的边。<ul><li>$1 \leq v, u \leq n$ 且 $w$ 为正整数。</li>
<li>如果存在这样的边则输出 &#34;<samp>ok</samp>&#34;（不含引号）（如果有多条权值为 $w$ 的边删去任意一条）。</li>
<li>否则操作非法，不进行操作并输出 &#34;<samp>failed</samp>&#34;（不含引号）。</li>
</ul></li>
<li>distance? $v$ $u$：查询结点 $v$ 到结点 $u$ 的最短路信息。<ul><li>$1 \leq v, u \leq n$。</li>
<li>输出一个整数 $l_m$。</li>
<li>$l_m$ 代表最短路的长度。</li>
<li>如果 $v = u$ 则 $l_m = 0$。</li>
<li>如果没有路可到达则 $l_m = -1$。</li>
</ul></li>
</ol>
# 输入格式


<p>第一行两个用空格隔开的正整数 $n, m$ 表示一共有 $n$ 个结点，$m$ 个操作。</p>
<p>接下来 $m$ 行，每行代表一个操作。</p>

# 输出格式


<p>对于每个操作，输出相应的结果。</p>

# 样例一


<h4>input</h4>
<pre>7 20
distance? 4 5
link 3 4 9
link 2 4 6
cut 2 4 6
distance? 5 7
link 6 7 8
link 6 4 1
link 2 1 2
link 2 3 5
link 7 5 2
link 2 5 9
distance? 4 5
distance? 5 6
distance? 5 4
distance? 2 7
link 1 2 7
distance? 4 6
cut 3 4 9
link 4 5 4
link 2 3 7

</pre>

<h4>output</h4>
<pre>-1
ok
ok
ok
-1
ok
ok
ok
ok
ok
ok
11
10
11
11
ok
1
ok
ok
ok

</pre>


# 样例二


<p>见样例数据下载，这组超良心数据中包含了许多你需要考虑的细节。</p>

# 样例三


<p>见样例数据下载</p>

# 限制与约定


<p>$1 \leq n \leq 100000, 1 \leq m \leq 400000$。</p>
<p>保证 link 和 cut 操作中的 $w$ 满足 $1 \leq w \leq 10000$，所以关于边权的计算不会超出 32 位有符号整数范围。</p>
<p><strong>时间限制：</strong>$5\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=63">样例数据下载</a></p>
