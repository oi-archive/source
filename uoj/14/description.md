# 题目描述

<p>DZY开始有 $n$ 个点，现在他对这 $n$ 个点进行了 $m$ 次操作，对于第 $i$ 个操作（从 $1$ 开始编号）有可能的三种情况：</p>
<ol><li>Add a b： 表示在 $a$ 与 $b$ 之间连了一条长度为 $i$ 的边（<strong>注意，$i$是操作编号</strong>）。保证 $1 \leq a, b \leq n$。</li>
<li>Delete k： 表示删除了当前图中边权最大的k条边。保证 $k$ 一定不会比当前图中边的条数多。</li>
<li>Return： 表示撤销第 $i-1$ 次操作。保证第 $1$ 次操作不是 Return 且第 $i-1$ 次不是 Return 操作。</li>
</ol><p>请你在每次操作后告诉DZY当前图的最小生成树边权和。如果最小生成树不存在则输出 $0$。</p>

# 输入格式


<p>第一行两个正整数 $n,m$。表示有 $n$ 个点 $m$ 个操作。
接下来 $m$ 行每行描述一个操作。</p>

# 输出格式


<p>对于每一个操作输出一行一个整数表示当前最小生成树边权和。</p>

# 样例一


<h4>input</h4>
<pre>2 2
Add 1 2
Return

</pre>


# output


<pre>1
0

</pre>


# 样例二


<h4>input</h4>
<pre>5 10
Add 2 1
Add 3 2
Add 4 2
Add 5 2
Add 2 3
Return
Delete 1
Add 2 3
Add 5 2
Return

</pre>

<h4>output</h4>
<pre>0
0
0
10
10
10
0
0
15
0

</pre>


# 样例三


<p>见样例数据下载</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>其他</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="3">$n \leq 10^3$</td><td rowspan="3">$m \leq 10^3$</td><td>只有Add操作</td></tr><tr><td>2</td><td></td></tr><tr><td>3</td><td></td></tr><tr><td>4</td><td>$n \leq 2 \times 10^5$</td><td>$m \leq 2 \times 10^5$</td><td rowspan="2">只有Add操作</td></tr><tr><td>5</td><td>$n \leq 3 \times 10^5$</td><td>$m \leq 5 \times 10^5$</td></tr><tr><td>6</td><td>$n \leq 2 \times 10^5$</td><td>$m \leq 2 \times 10^5$</td><td rowspan="2">没有Return操作</td></tr><tr><td>7</td><td>$n \leq 3 \times 10^5$</td><td>$m \leq 5 \times 10^5$</td></tr><tr><td>8</td><td>$n \leq 2 \times 10^5$</td><td>$m \leq 2 \times 10^5$</td><td></td></tr><tr><td>9</td><td rowspan="2">$n \leq 3 \times 10^5$</td><td rowspan="2">$m \leq 5 \times 10^5$</td><td></td></tr><tr><td>10</td><td></td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$64\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=14">样例数据下载</a></p>
