# 题目描述

<p>如果一个<strong>无自环无重边无向连通图</strong>的任意一条边最多属于一个简单环，我们就称之为仙人掌。所谓简单环即不经过重复的结点的环。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/utility/what-is-cactus.png" alt="什么是仙人掌"/></p>
<p>现在九条可怜手上有一张<strong>无自环无重边的无向连通图</strong>，但是她觉得这张图中的边数太少了，</p>
<p>所以她想要在图上连上一些新的边。同时为了方便的存储这张无向图，图中的边数又不能太多。</p>
<p>经过权衡，她想要加边后得到的图为一棵仙人掌。不难发现合法的加边方案有很多，可怜想要知道总共有多少不同的加边方案。两个加边方案是不同的当且仅当一个方案中存在一条另一个方案中没有的边。</p>

# 输入格式


<p>多组数据，第一行输入一个整数 $T$ 表示数据组数。</p>
<p>每组数据第一行输入两个整数 $n, m$，表示图中的点数与边数。</p>
<p>接下来 $m$ 行，每行两个整数 $u, v(1 \le u, v \le n, u \ne v)$ 表示图中的一条边。保证输入的图连通且没有自环与重边。</p>

# 输出格式


<p>对于每组数据，输出一个整数表示方案数，当然方案数可能很大，请对 $998244353$ 取模后输出。</p>

# 样例一


<h4>input</h4>
<pre>2
3 2
1 2
1 3
5 4
1 2
2 3
2 4
1 5

</pre>

<h4>output</h4>
<pre>2
8

</pre>

<h4>explanation</h4>
<p>对于第一组样例合法加边的方案有 $\{\}, \{(2, 3)\}$，共 $2$ 种。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$\sum n$</th>
<th>$m$</th>
<th>其他约定</th>
</tr></thead><tbody><tr><td>1</td><td>$\le 5$</td><td>$\le 10$</td><td rowspan="3">无</td></tr><tr><td>2</td><td rowspan="2">$\le 2000$</td><td rowspan="2">$\le 2 \times 10^5$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="4">$\le 10^5$</td><td rowspan="4">$= n - 1$</td><td rowspan="2">图为一条链</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">无</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$\le 5 \times 10^5$</td><td rowspan="3">$\le 10^6$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于 100% 的数据，保证 $1 \le m \le \frac{n(n−1)}{2}, \sum m \le 10^6$。</p>
<p><strong>注意 $T$ 可能较大，请注意控制初始化的复杂度。</strong></p>
<p>样例二的四组数据依次满足第 2, 4, 6, 8 个点的条件。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=290">样例数据下载</a></p>
