# 题目描述

<p>在神秘的大清，有更多的ddl，就会有更多咕咕咕的方法。</p>
<p>准确的说，ddl是一棵大小为 $n$ 的树，第一个节点是网络科学，第二个节点是博弈论...</p>
<p>Lyra 的暑期计划（除了陪 Evan 之外）是一个每个元素在 $[1,n]$ 的序列，她计划完成一个长度为偶数的子区间的ddl，并且咕咕咕掉剩下的。</p>
<p>她会给区间内的ddl两两配对，两个ddl如果很接近，那么她就只需要把第一个ddl要交的作业稍作修改，在网络学堂上上传到第二个ddl。</p>
<p>Lyra 很聪明，所以她总是能巧妙的把区间内的ddl两两匹配使得匹配的ddl之间在树上的距离之和（唯一简单路上的边权和）最小。每个长度为偶数的区间的完成时间定义为最小配对方法中每对匹配点间距离的总和。</p>
<p>作为 Lyra 的朋友，你要帮她求序列每个长度为偶数的区间的ddl的完成时间之和。</p>

# 输入格式


<p>第一行两个整数 $n, m$ 表示树的大小和序列的长度。</p>
<p>接下来 $n-1$ 行每行三个整数 $u, v, w$ 表示一条连接 $u, v$ 长度为 $w$ 的树边。</p>
<p>接下来一行 $m$ 个整数表示序列。</p>
<p><strong>注意：本题输入可能很大，建议采用较为快速的读入方式。</strong></p>

# 输出格式


<p>一行一个整数表示答案，由于答案可能很大，输出其对 $998244353$ 取模的结果。</p>

# 样例一


<h4>input</h4>
<pre>4 4
1 2 1
2 3 2
3 4 1
2 3 1 4

</pre>

<h4>output</h4>
<pre>11

</pre>

<h4>explanation</h4>
<p>一共只有 $4$ 个区间需要计算，点集分别为 $\{2, 3\}, \{3, 1\}, \{1, 4\}, \{2, 3, 1, 4\}$，
最小完成时间分别为 $2, 3, 4, 2$，于是总和为 $11$。</p>

# 样例二


<h4>input</h4>
<pre>7 7
1 2 5
1 3 4
2 4 3
2 5 2
3 6 1
3 7 2
1 5 3 6 7 5 1

</pre>

<h4>output</h4>
<pre>102

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>本题采用捆绑测试，只有通过一个子任务的全部测试点才可以得到子任务的得分。</p>
<p>对于全部数据 $1 \leq n, m \leq 10^5; 1 \leq w \leq 10^9.$</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th width="10%">子任务</th>
<th width="10%">分值</th>
<th width="13%">$n$的规模</th>
<th width="13%">$m$的规模</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td>5</td><td>$\leq 100$</td><td>$\leq 100$</td><td rowspan="4">无</td>
</tr><tr><td>2</td><td>15</td><td>$\leq 1000$</td><td>$\leq 1000$</td>
</tr><tr><td>3</td><td>15</td><td>$\leq 10^5$</td><td>$\leq 100$</td>
</tr><tr><td>4</td><td>15</td><td>$\leq 1000$</td><td rowspan="4">$\leq 10^5$</td>
</tr><tr><td>5</td><td>15</td><td rowspan="3">$\leq 10^5$</td><td>$n=m$ 且序列为一个 $1 \sim n$ 的排列</td>
</tr><tr><td>6</td><td>15</td><td>树的生成方式是随机一条边若不形成环则加入，形成树为止</td>
</tr><tr><td>7</td><td>20</td><td>无</td>
</tr></tbody></table></div>


<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=388">样例数据下载</a></p>
