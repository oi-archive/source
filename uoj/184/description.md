# 题目描述

<p>小Y来到了一个新的城市旅行。她发现了这个城市的布局是网格状的，也就是有 $n$ 条从东到西的道路和 $m$ 条从南到北的道路，这些道路两两相交形成 $n \times m$ 个路口 $(i,j)(1 \leq i \leq n,1 \leq j \leq m)$。</p>
<p>她发现不同的道路路况不同，所以通过不同的路口需要不同的时间。通过调查发现，从路口 $(i,j)$ 到路口 $(i,j+1)$ 需要时间 $r_{i,j}$，从路口 $(i,j)$ 到路口 $(i+1,j)$ 需要时间 $c_{i,j}$。注意这里的道路是双向的，也就是从路口 $(i,j+1)$ 到路口 $(i,j)$ 需要时间同样是 $r_{i,j}$。</p>
<p>小Y有 $q$ 个询问，她想知道从路口 $(x_1,y_1)$ 到路口 $(x_2,y_2)$ 最少需要花多少时间。</p>

# 输入格式


<p>第一行包含 2 个正整数 $n,m$ ，表示城市的大小。</p>
<p>接下来 $n$ 行，每行包含 $m-1$ 个整数，第 $i$ 行第 $j$ 个正整数表示从一个路口到另一个路口的时间 $r_{i,j}$。</p>
<p>接下来 $n-1$ 行，每行包含 $m$ 个整数，第 $i$ 行第 $j$ 个正整数表示从一个路口到另一个路口的时间 $c_{i,j}$。</p>
<p>接下来一行，包含1个正整数 $q$ ，表示小Y的询问个数。</p>
<p>接下来 $q$ 行，每行包含4个正整数 $x_1,y_1,x_2,y_2$，表示两个路口的位置。</p>

# 输出格式


<p>输出共 $q$ 行，每行包含一个整数表示从一个路口到另一个路口最少需要花的时间。</p>

# 样例一


<h4>input</h4>
<pre>2 2
2
3
6 4
2
1 1 2 2
1 2 2 1

</pre>

<h4>output</h4>
<pre>6
7

</pre>


# 样例二


<h4>input</h4>
<pre>2 3
558 163
102 2000
461 1732 561
2
2 1 2 3
1 2 2 2

</pre>

<h4>output</h4>
<pre>1743
1121

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n \times m$</th><th>$q$</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td rowspan="2">$\leq 10^3$</td><td rowspan="2">$\leq 10^3$</td><td rowspan="2"></td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="8">$\leq 2 \times 10^4$</td><td rowspan="8">$\leq 10^5$</td><td rowspan="3">$\min(n,m) \leq 4$</td></tr><tr><td>4</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5"></td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有的测试数据，保证相邻路口之间的时间不超过$10^4$，即 $1 \leq r_{i,j},c_{i,j} \leq 10^4$。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=184">样例数据下载</a></p>
