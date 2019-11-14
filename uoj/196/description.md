# 题目描述

<p>小Yuuka遇到了一个题目：有一个序列 $a_1,a_2,...,a_n$，$q$ 次操作，每次把一个区间内的数改成区间内的最大值，问最后每个数是多少。小Yuuka很快地就使用了线段树解决了这个问题。</p>
<p>于是充满智慧的小Yuuka想，如果操作是随机的，即在这 $q$ 次操作中每次等概率随机地选择一个区间 $[l,r] (1 \leq l \leq r \leq n)$，然后将这个区间内的数改成区间内最大值（注意这样的区间共有 $\frac{n(n+1)}{2}$ 个），最后每个数的期望大小是多少呢？</p>
<p>小Yuuka非常热爱随机，所以她给出的输入序列也是随机的（随机方式见数据规模和约定）。</p>
<p>对于每个数，输出它的期望乘 $\left(\frac{n(n+1)}{2}\right)^q$ 再对 $10^9+7$ 取模后的值。</p>

# 输入格式


<p>第一行包含 $2$ 个正整数 $n,q$，表示序列里数的个数和操作的个数。</p>
<p>接下来 $1$ 行，包含 $n$ 个非负整数 $a_1,a_2,...,a_n$。</p>

# 输出格式


<p>输出共 $1$ 行，包含 $n$ 个整数，表示每个数的答案。</p>

# 样例一


<h4>input</h4>
<pre>5 5 
1 5 2 3 4 

</pre>

<h4>output</h4>
<pre>3152671 3796875 3692207 3623487 3515626

</pre>


# 样例二


<p>见样例数据下载。</p>
<p>注意样例输入输出1和2不满足数据规模和约定中的生成方式。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有的测试数据，保证序列中数的大小不超过 $10^9$，即 $a_i \leq 10^9$，并且每个数是 $0$ 到 $10^9$ 之间的随机整数。 </p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$q$</th></tr></thead><tbody><tr><td>1</td><td>$\leq 5$</td><td>$\leq 5$</td></tr><tr><td>2</td><td>$\leq 8$</td><td rowspan="9">$\leq 400$</td></tr><tr><td>3</td><td>$\leq 12$</td></tr><tr><td>4</td><td>$\leq 30$</td></tr><tr><td>5</td><td>$\leq 50$</td></tr><tr><td>6</td><td rowspan="2">$\leq 100$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$\leq 400$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=196">样例数据下载</a></p>
