# 题目描述

<p>令 $N = \prod_{i = 1}^{n} p_i^{a_i}$，$M = \prod_{i = 1}^{n} p_i^{b_i}$，其中 $p_i$ 是两两不同的素数。</p>
<p>求将 $N$ 表示成 $k$ 个正整数的乘积的方案数，也就是 $N = \prod_{i = 1}^k x_i$ 的解的个数，答案对 $10^9 + 21$ 取模。</p>
<p>对于子问题 $1$，要求对于所有整数 $i$ 满足 $1 \leq i &lt; k$，都有 $x_i &lt; x_{i + 1}$。</p>
<p>对于子问题 $2$，要求对于所有整数 $i$ 满足 $1 \leq i &lt; k$，都有 $x_i \leq x_{i + 1}$。</p>
<p>对于两个子问题都要求对于所有整数 $i$ 满足 $1 \leq i \leq k$ 都有 $x_i \nmid M$，即 $x_i$ 不是 $M$ 的约数。</p>

# 输入格式


<p>第一行两个正整数 $n, k$。</p>
<p>接下来一行 $n$ 个非负整数，第 $i$ 个整数表示 $a_i$。</p>
<p>接下来一行 $n$ 个非负整数，第 $i$ 个整数表示 $b_i$。</p>
<p>输入中没有给出 $p_1, \dots, p_n$，显然 $p_i$ 的取值并不影响答案。</p>

# 输出格式


<p>一行两个整数，分别表示子问题 1 和 2 的答案。</p>

# 样例一


<h4>input</h4>
<pre>5 3
5 5 4 5 5
3 0 3 2 3

</pre>

<h4>output</h4>
<pre>295164 295326

</pre>


# 样例二


<h4>input</h4>
<pre>10 5
13 11 17 7 9 2 11 11 10 12
7 9 4 15 18 4 9 7 4 2

</pre>

<h4>output</h4>
<pre>75340090 59089865

</pre>



# 限制与约定


<p>共 10 个测试点，只有子问题 1 答案正确将获得 3 分，只有子问题 2 答案正确将获得 6 分，都正确将获得 10 分。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$a_i$</th>
<th>$b_i$</th>
<th>$k$</th>
</tr></thead><tbody><tr><td>1</td><td>$\leq 5$</td><td>$\leq 5$</td><td>$\leq 5$</td><td>$\leq 3$</td></tr><tr><td>2</td><td>$\leq 10$</td><td>$\leq 20$</td><td>$\leq 20$</td><td>$\leq 5$</td></tr><tr><td>3</td><td>$= 1$</td><td>$\leq 10^{18}$</td><td>$\leq 10^{18}$</td><td>$\leq 25$</td></tr><tr><td>4</td><td rowspan="7">$\leq 50$</td><td>$\leq 10^3$</td><td rowspan="2">$= 0$</td><td>$\leq 20$</td></tr><tr><td>5</td><td>$\leq 10^{18}$</td><td>$\leq 25$</td></tr><tr><td>6</td><td>$\leq 10^3$</td><td>$\leq 10^3$</td><td>$\leq 10$</td></tr><tr><td>7</td><td rowspan="4">$\leq 10^{18}$</td><td rowspan="4">$\leq 10^{18}$</td><td>$\leq 10$</td></tr><tr><td>8</td><td>$\leq 15$</td></tr><tr><td>9</td><td>$\leq 20$</td></tr><tr><td>10</td><td>$\leq 25$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>中国国家集训队互测2015 - By 杜瑜皓</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=99">样例数据下载</a></p>
