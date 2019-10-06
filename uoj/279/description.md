# 题目描述

<p>定好了难度，雄心勃勃的吉米多出题斯基开始寻找智慧的神犇星球的居民出题。</p>
<p>然而吉米多出题斯基没有料到，神犇星球的居民告诉吉米多出题斯基：“今年神犇星球经济不景气，大家都想宅在家里，哪有心思出来出题呢？”</p>
<p>为了挽救这一局面，吉米多出题斯基决定为神犇星球建一些高速传送通道促进该星球各地区之间交流题目。</p>
<p>神犇星球有 $n$ 座小城。对于任意两座小城 $v, u$（$v \neq u$），吉米多出题斯基想在 $v, u$ 之间建立一个传送时间为 $w(v, u)$ 的<strong>无向</strong>传送通道，其中 $w(v, u)$ 为不超过 $k$ 的非负整数。建成后，神犇星球的居民可从一座小城出发经过一个或若干个传送通道到达另一座小城交流题目，花费的时间为所有经过的传送通道的传送时间之和。</p>
<p>吉米多出题斯基还没有决定每一个传送通道的传送时间取值，只是对于任意两座小城 $v, u$，决定了从 $v$ 出发到达 $u$ 的最短时间要恰好等于 $d(v, u)$。但吉米多出题斯基日理万机，于是他找到了你 —— 风璃殇做不出题耶维奇，请你帮助吉米多出题斯基数一数有多少种不同的满足条件的传送通道建设方案吧！</p>
<p>由于方案数可能很大，你只用输出方案数对 $998244353$（$7 \times 17 \times 2^{23}+1$，一个质数）取模后的结果。</p>

# 输入


<p>第一行两个整数 $n, k$。保证 $n \ge 1, k \ge 0$。</p>
<p>接下来 $n$ 行，每行有 $n$ 个非负整数，第 $i$ 行的 第 $j$ 个数表示 $d(i,j)$ 的值。</p>

# 输出


<p>输出一行，一个整数，表示方案数对 $998244353$ 取模的结果。如果无解，则方案数为 $0$。</p>

# 样例一


<h4>input</h4>
<pre>3 3
0 2 1
2 0 3
1 3 0

</pre>

<h4>output</h4>
<pre>1

</pre>


# 样例二


<h4>input</h4>
<pre>3 5
0 3 4
3 0 1
4 1 0

</pre>

<h4>output</h4>
<pre>2

</pre>


# 样例三


<p>见样例数据下载，限制与约定跟<strong>子任务 3</strong> 相同。</p>

# 样例四


<p>见样例数据下载，限制与约定跟<strong>子任务 3</strong> 相同。</p>

# 限制与约定


<p>对于所有数据，有 $1\leq n\leq 400, 0\leq k\leq 10^9, 0\leq d(u,v)\leq 10^{9}$</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$n$</th>
<th>$k$</th>
<th>其他限制</th>
</tr></thead><tbody><tr><td>1</td><td>30</td><td>$1 \leq n \leq 4$</td><td>$0\leq k\leq 5$</td><td></td></tr><tr><td>2</td><td>30</td><td>$1 \leq n \leq 400$</td><td>$0\leq k\leq 10^9$</td><td>对于所有 $u\neq v$，有 $d(u,v)\geq 1$</td></tr><tr><td>3</td><td>40</td><td>$1 \leq n \leq 400$</td><td>$0 \leq k \leq 10^9$</td><td></td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=279">样例数据下载</a></p>
