# 题目描述

<p>出题人 01 很喜欢加法，也很喜欢异或运算（即 C/C++ 里的 <code>^</code> 运算符）。有天他一拍脑袋：把两个运算混一起，岂不是妙极了？</p>
<p>对于一个序列 $b_1, \dots, b_m$，他希望你将序列 $b$ 划分为 $k$ 段连续非空子序列，使得每一段的异或和之和最小。即，他想知道在所有满足 $0 = p_0 &lt; p_1 &lt; \cdots &lt; p_k = m$ 条件的序列 $p$ 中下式的最小值：
$$
\sum_{i=1}^{k} (b_{p_{i-1} + 1} \mathbin{\mathrm{xor}} \cdots \mathbin{\mathrm{xor}} b_{p_i})
$$
这个最小值即称为这个序列的<strong>妙妙值</strong>。</p>
<p>但是这个问题非常简单，于是出题人 01 找来了一个长度恰好为 $n$ 的非负整数序列 $a_1, \dots, a_n$。他想考考你，$a$ 的每个前缀 $a_1, \dots, a_j$ （$k \le j \le n$）的妙妙值分别是多少呢？</p>

# 输入格式


<p>第一行两个正整数 $n,k$，含义同题面。</p>
<p>接下来一行 $n$ 个非负整数，第 $i$ 个非负整数表示 $a_i$。</p>

# 输出格式


<p>第一行 $n-k+1$ 个整数，分别表示前 $j = k, k+1, \dots, n$ 个元素组成的序列的妙妙值。</p>

# 样例一


<h4>input</h4>
<pre>6 2
1 1 4 5 1 4

</pre>

<h4>output</h4>
<pre>2 4 1 0 4

</pre>

<h4>explanation</h4>
<p>对于序列 $a_1, \dots, a_6$,可以将序列划分为 $a_1, a_2$ 和 $a_3, a_4, a_5, a_6$ 两段。</p>
<p>此时答案为 $(1 \mathbin{\mathrm{xor}} 1)+(4 \mathbin{\mathrm{xor}} 5 \mathbin{\mathrm{xor}} 1 \mathbin{\mathrm{xor}} 4)=0+4=4$。</p>
<p>注意 $a_1, a_2, a_3, a_4, a_5$ 和 $a_6$ 也是一种合法的划分方案。</p>

# 样例二


<p>见下发文件。</p>
<p>数据范围同测试点 3 ~ 4。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>特殊性质</th></tr></thead><tbody><tr><td>1 ~ 2</td> <td>$\le 15$</td>  <td rowspan="2">无</td></tr><tr><td>3 ~ 4</td> <td>$\le 5000$</td> </tr><tr><td>5 ~ 6</td> <td rowspan="3">$\le 60000$</td> <td>$a_i \lt 2^8$</td> </tr><tr><td>7 ~ 8</td> <td>$a_i \lt 2^{12}$</td> </tr><tr><td>9 ~ 10</td> <td>无</td> </tr></tbody></table></div>

<p>对于所有测试点，满足 $1 \le k \le n \le 60000, k \le 8,a_i &lt; 2^{16}$</p>
<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=549">样例数据下载</a></p>
