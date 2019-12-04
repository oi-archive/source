# 题目描述

<p>组合数 $C_n^m$ 表示的是从 $n$ 个物品中选出 $m$ 个物品的方案数。举个例子，从 $(1,2,3)$ 三个物品中选择两个物品可以有 $(1,2),(1,3),(2,3)$ 这三种选择方法。根据组合数的定义，我们可以给出计算组合数 $C_n^m$ 的一般公式：</p>
<p>$$C_n^m=\frac{n!}{m!(n-m)!}$$</p>
<p>其中 $n!=1\times2\times\cdots\times n$；特别地，定义 $0!=1$。</p>
<p>小葱想知道如果给定 $n,m$ 和 $k$，对于所有的 $0\leq i\leq n,0\leq j\leq \min \left ( i, m \right )$ 有多少对 $(i,j)$ 满足 $C_i^j$ 是 $k$ 的倍数。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行有两个整数 $t,k$，其中 $t$ 代表该测试点总共有多少组测试数据，$k$ 的意义见问题描述。</p>
<p>接下来 $t$ 行每行两个整数 $n,m$，其中 $n,m$ 的意义见问题描述。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>$t$ 行，每行一个整数代表所有的 $0\leq i\leq n,0\leq j\leq \min \left ( i, m \right )$ 中有多少对 $(i,j)$ 满足 $C_i^j$ 是 $k$ 的倍数。</p>

# 样例一


<h4>input</h4>
<pre>1 2
3 3

</pre>

<h4>output</h4>
<pre>1

</pre>

<h4>explanation</h4>
<p>在所有可能的情况中，只有 $C_2^1=2$ 是 $2$的倍数。</p>

# 样例二


<h4>input</h4>
<pre>2 5
4 5
6 7

</pre>

<h4>output</h4>
<pre>0
7

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">$k$</th><th rowspan="1">$t$</th></tr></thead><tbody><tr><td rowspan="1">$1$</td><td rowspan="2">$\leq3$</td><td rowspan="2">$\leq3$</td><td rowspan="1">$=2$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$2$</td><td rowspan="1">$=3$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$3$</td><td rowspan="2">$\leq7$</td><td rowspan="2">$\leq7$</td><td rowspan="1">$=4$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$4$</td><td rowspan="1">$=5$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$5$</td><td rowspan="2">$\leq10$</td><td rowspan="2">$\leq10$</td><td rowspan="1">$=6$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$6$</td><td rowspan="1">$=7$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$7$</td><td rowspan="2">$\leq20$</td><td rowspan="2">$\leq100$</td><td rowspan="1">$=8$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$8$</td><td rowspan="1">$=9$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$9$</td><td rowspan="2">$\leq25$</td><td rowspan="2">$\leq2000$</td><td rowspan="1">$=10$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$10$</td><td rowspan="1">$=11$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$11$</td><td rowspan="2">$\leq60$</td><td rowspan="2">$\leq20$</td><td rowspan="1">$=12$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$12$</td><td rowspan="1">$=13$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$13$</td><td rowspan="4">$\leq100$</td><td rowspan="2">$\leq25$</td><td rowspan="1">$=14$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$14$</td><td rowspan="1">$=15$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$15$</td><td rowspan="2">$\leq60$</td><td rowspan="1">$=16$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$16$</td><td rowspan="1">$=17$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$17$</td><td rowspan="4">$\leq2000$</td><td rowspan="2">$\leq100$</td><td rowspan="1">$=18$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$18$</td><td rowspan="1">$=19$</td><td rowspan="1">$\leq10^4$</td></tr><tr><td rowspan="1">$19$</td><td rowspan="2">$\leq2000$</td><td rowspan="1">$=20$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">$20$</td><td rowspan="1">$=21$</td><td rowspan="1">$\leq10^4$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=263">样例数据下载</a></p>
