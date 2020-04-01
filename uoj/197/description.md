# 题目描述

<p>小Y是一个充满智慧的女孩子，但是她只会使用串并联的方法计算两个节点之间的电阻。 </p>
<p>现在小Y有一个电阻网络，问有多少点对 $(u,v)(u \neq v)$ 之间的电阻可以用串并联的方法计算出来。</p>
<p>我们来形式化地定义一下点对 $(u,v)(u \neq v)$  之间的电阻能否用串并联的方法计算出来。首先我们把电阻网络看成一个 $n$ 个点 $m$ 条边的图（每个电阻对应一条边）。令 $S$ 表示从 $u$ 到 $v$ 的所有简单路径(不经过重复的点的路径)上点的并集，也就是对于一个点 $x$ ，如果存在一条从 $u$ 到 $v$ 的简单路径经过这个点，那么它就在集合  $S$ 中。如果 $S$ 非空且 $S$ 的导出子图是 $u,v$ 为端点的二端串并联图，那么 $u,v$ 之间的电阻就能用串并联方法计算。</p>
<p>一个有两个不同端点 $s,t$ 的图被称为二端图，其中一个称为源点，另一个称为汇点。两个二端图 $X,Y$ 并联(parallel composition)是指建一个新图，把 $X$ 和 $Y$ 的源点和汇点分别合并起来。两个二端图 $X,Y$ 串联(series  composition)是指建一个新图，把 $X$ 的汇点和 $Y$ 的源点合并起来。由若干个两个点一条边的二端图经过一系列串并联变化之后形成的图称为二端串并联图。 </p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/197/dianzu.png" alt="QAQ"/></p>
<p>集合 $S$ 的导出子图点集为 $S$ ，边集由原图中两个端点都在 $S$ 中的边构成。 </p>

# 输入格式


<p>第一行包含 $2$ 个正整数 $n,m$ ，表示电阻网络中的节点数和电阻数。</p>
<p>接下来 $m$ 行，每行包含 $2$ 个正整数 $u,v(1 \leq u,v \leq n, u \neq v)$ ，表示有一个电阻在节点 $u$ 和 $v$ 之间。</p>

# 输出格式


<p>输出共 $1$ 行，表示答案，即有多少点对之间的电阻可以使用串并联的方法计算出来。 </p>

# 样例一


<h4>input</h4>
<pre>6 6
1 2
1 3
1 4
2 3
2 4
5 6

</pre>

<h4>output</h4>
<pre>6

</pre>

<h4>explanation</h4>
<p>可行的点对有 $(1,2),(1,3),(1,4),(2,3),(2,4),(5,6)$。</p>

# 样例二


<h4>input</h4>
<pre>13 18 
1 2 
2 3 
2 4 
3 4 
3 5 
4 5 
5 6 
5 7 
5 8 
6 8 
7 8 
8 9 
10 11 
10 12 
10 13 
11 12 
11 13 
12 13

</pre>

<h4>output</h4>
<pre>25

</pre>


# 样例三


<p>见样例数据下载。</p>

# 样例四


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td>$\leq 10$</td><td>$\leq 10$</td><td rowspan="2">保证原图连通，并且不存在一个点删去之后使得原图不连通</td></tr><tr><td>2</td><td rowspan="2">$\leq 100$</td><td rowspan="2">$\leq 100$</td></tr><tr><td>3</td><td rowspan="2"></td></tr><tr><td>4</td><td>$\leq 10^3$</td><td>$\leq 10^3$</td></tr><tr><td>5</td><td rowspan="6">$\leq 10^5$</td><td rowspan="6">$\leq 10^5$</td><td rowspan="3">保证原图连通，并且不存在一个点删去之后使得原图不连通</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3"></td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=197">样例数据下载</a></p>
