# 题目描述

<p>这天，跳蚤国王决定亲自下江南视察当地跳蚤的生活情况。</p>
<p>江南一共有 $n$ 座城市编号为$1$到 $n$，城市之间有一些道路相连。其道路结构可以抽象为一棵仙人掌。如果一个无向连通图的任意一条边最多属于一个简单环，我们就称之为仙人掌。所谓简单环即不经过重复的结点的环。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/utility/what-is-cactus.png" alt="什么是仙人掌"/></p>
<p>现在跳蚤国王在$1$号城市准备出发。为了制定合理的下江南路线，跳蚤国王时不时问他的助手伏特：“从$1$号城市出发经过恰好 $l$ 条道路的简单路径有多少条？”。所谓简单路径即不经过重复的结点的路径。</p>
<p>这可难倒了伏特，请你对于 $l = 1, 2, \dots, (n-1)$ 求出相应的答案。只用输出答案对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）取模后的值。</p>

# 输入格式


<p>第$1$行两个正整数$n, m$表示城市的个数和道路的条数。保证$n \geq 2$。</p>
<p>接下来$m$行每行两个正整数$v, u$（$1 \leq v, u \leq n$）表示一条连接城市$v$和$u$的道路。</p>
<p>保证输入的图是一棵仙人掌，保证没有自环，但可能有重边。</p>

# 输出格式


<p>输出 $n - 1$ 行，第 $i$ 行包含一个整数表示 $l = i$ 时的答案（$1 \leq i \leq n - 1$）。</p>

# 样例一


<h4>input</h4>
<pre>3 3
1 2
2 3
3 1

</pre>

<h4>output</h4>
<pre>2
2

</pre>

<h4>explanation</h4>
<p>这是一个三元环，从 $1$ 号点出发走 $l$ 条边有顺时针走和逆时针走两种方式。</p>

# 样例二


<h4>input</h4>
<pre>10 13
1 3
5 8
5 10
2 8
9 6
9 6
2 1
9 4
5 2
4 5
3 2
7 10
10 9

</pre>

<h4>output</h4>
<pre>2
4
6
9
14
16
8
1
0

</pre>


# 样例三


<h4>input</h4>
<pre>2 2
1 2
1 2

</pre>

<h4>output</h4>
<pre>2

</pre>

<h4>explanation</h4>
<p>注意可能有重边。</p>

# 样例四


<p>输入输出数据见样例数据下载。另外，里面附有一张png图片作为该样例的解释。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>其他</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n \leq 14$</td><td rowspan="2"></td></tr><tr><td>2</td></tr><tr><td>3</td><td>$n \leq 100$</td><td></td></tr><tr><td>4</td><td rowspan="2">$n \leq 1000$</td><td rowspan="2"></td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$n \leq 100000$</td><td rowspan="2">保证对于$1 \leq i &lt; n$，$i$ 与 $i + 1$ 之间存在至少一条道路直接相连</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3"></td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>虽然我没有给 $m$ 的范围，但是熟悉仙人掌的小朋友都知道对于仙人掌肯定满足 $n - 1 \leq m \leq 2n - 2$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=23">样例数据下载</a></p>
