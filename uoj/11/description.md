# 题目描述

<p>ydc有一棵$n$个结点的黑白相间的大树，从$1$到$n$编号。</p>
<p>这棵黑白树中有$m$个黑点，其它都是白点。</p>
<p>对于一个黑点我们定义他的好朋友为离他最远的黑点。如果有多个黑点离它最远那么都是它的好朋友。两点间的距离定义为两点之间的最短路的长度。</p>
<p>现在你要摧毁一个白点。</p>
<p>摧毁后有一些黑点会不高兴。一个黑点不高兴当且仅当他不能到达任何一个在摧毁那个白点前的好朋友。</p>
<p>请你最大化不高兴的黑点数。</p>

# 输入格式


<p>第一行包含两个正整数$n,m$ $(2\le m &lt; n)$，分别表示树的结点数，以及黑点数。</p>
<p>接下来$1$行，有$m$个互不相同的正整数，表示每个黑结点的编号。</p>
<p>接下来$n-1$行，每行三个正整数$u,v,l$，表示结点 $u,v$ 之间有一条无向边长度为 $l$。</p>

# 输出格式


<p>共一行，两个数，分别表示：最多能让多少个黑点不高兴，以及有多少种方式达到这种效果。（即统计有多少个白点摧毁后能使黑点不高兴的个数最大化）</p>

# 样例一


<h4>input</h4>
<pre>8 5
7 2 5 4 8
1 2 1
2 3 2
1 4 1
4 5 2
1 6 1
6 7 8
6 8 10

</pre>

<h4>output</h4>
<pre>5 1

</pre>


# 样例二


<h4>input</h4>
<pre>5 3
2 3 1
1 2 1
2 3 1
3 4 1
4 5 1

</pre>

<h4>output</h4>
<pre>0 2

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与规定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>备注</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n \le 10^2$</td><td rowspan="2"></td>
</tr><tr><td>2</td>
</tr><tr><td>3</td><td rowspan="3">$n \le 10^3$</td><td rowspan="3"></td>
</tr><tr><td>4</td>
</tr><tr><td>5</td>
</tr><tr><td>6</td><td>$n \le 10^5$</td><td>保证是一条链</td>
</tr><tr><td>7</td><td>$n \le 10^5$</td><td>$2 \le m \le 10$</td>
</tr><tr><td>8</td><td rowspan="3">$n \le 10^5$</td><td rowspan="3"></td>
</tr><tr><td>9</td>
</tr><tr><td>10</td>
</tr></tbody></table></div>

<p>保证对于每条边，边权满足 $1 \le l \le 1000$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=11">样例数据下载</a></p>
