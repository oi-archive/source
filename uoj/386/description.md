# 题目描述

<p>为了固定S**p*鸽鸽，whx和zzt来到鸽具商店选购鸽子固定器。</p>
<p>鸽具商店有 $n$ 个不同大小的固定器，现在可以选择至多 $m$ 个来固定S**p*鸽鸽。每个固定器有大小 $s_i$ 和牢固程度 $v_i$。</p>
<p>如果他们选购的固定器大小不一或是不牢固，固定S**p*鸽鸽的时候肯定会很头疼，所以定义选择的物品总牢固程度和的 $d_v$ 次方减大小极差的 $d_s$ 次方为这个方案的价值，求不同选购方案中，价值的最大值。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/386/gezigudingqi.jpeg" alt="鸽子固定器"/></p>

# 输入格式


<p>第一行四个正整数 $n,m,d_s,d_v$。</p>
<p>接下来 $n$ 行，每行两个正整数 $s_i,v_i$，表示第 $i$ 个固定器的大小和牢固程度。</p>

# 输出格式


<p>输出一行，包含一个整数，表示<strong>价值</strong>的最大值。</p>

# 样例一


<h4>input</h4>
<pre>3 2 1 1
4 2
1 3
5 10

</pre>

<h4>output</h4>
<pre>11

</pre>


# 样例二


<h4>input</h4>
<pre>3 2 2 2
4 2
1 3
5 10

</pre>

<h4>output</h4>
<pre>153

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$n$ 的规模</th>
<th>$m$ 的规模</th>
<th>$d_s,d_v$ 的规模</th>
<th>$s_i,v_i$ 的规模</th>
<th>其他约定</th>
</tr></thead><tbody><tr><td>1</td><td>5</td><td>$1 \leq n \leq 10$</td><td rowspan="6">$1 \leq m \leq \min(50, n)$</td><td rowspan="2">$d_s = d_v = 2$</td><td rowspan="6"><strong>$1 \leq s_i,v_i \leq 10^7$</strong></td><td rowspan="3">无</td>
</tr><tr><td>2</td><td>5</td><td>$1 \leq n \leq 1000$</td>
</tr><tr><td>3</td><td>10</td><td rowspan="4">$1 \leq n \leq 2 \times 10^5$</td><td>$d_s=d_v=1$</td>
</tr><tr><td>4</td><td>25</td><td>$d_s=d_v=2$</td><td>$s_i,v_i$分别在某个范围内均匀随机生成</td>
</tr><tr><td>5</td><td>25</td><td>$d_s=1,d_v=2$</td><td rowspan="2">无</td>
</tr><tr><td>6</td><td>30</td><td>$1 \leq d_s,d_v \leq 2$</td>
</tr></tbody></table></div>

<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=386">样例数据下载</a></p>
