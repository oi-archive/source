# 题目描述

<p>给定 $p, n, l, r$，其中 $p$ 是质数。请对 $0$ 到 $p - 1$ 的所有值 $a$，输出满足 $l \le x \le r$ 且 ${x \choose n} \equiv a \pmod{p}$ 的 $x$ 的个数对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）取模后的结果。其中 ${x \choose n}$ 是二项式系数，即 $x$ 个数里选 $n$ 个的方案数。</p>

# 输入格式


<p>一行四个非负整数，分别表示 $p, n, l, r$，保证 $l \le r$。</p>

# 输出格式


<p>$p$ 行，第 $i$ 行表示 $a = i - 1$ 时的答案。</p>

# 样例一


<h4>input</h4>
<pre>7 3 1 7

</pre>

<h4>output</h4>
<pre>3
1
0
1
1
0
1

</pre>

<h4>explanation</h4>
<p>${1 \choose 3} = {2 \choose 3} = 0 \equiv 0 \pmod{7}$</p>
<p>${3 \choose 3} = 1 \equiv 1 \pmod{7}$</p>
<p>${4 \choose 3} = 4 \equiv 4 \pmod{7}$</p>
<p>${5 \choose 3} = 10 \equiv 3 \pmod{7}$</p>
<p>${6 \choose 3} = 20 \equiv 6 \pmod{7}$</p>
<p>${7 \choose 3} = 35 \equiv 0 \pmod{7}$</p>
<p>故模 $7$ 意义下值为$0$的有三个，值为 $1, 3, 4, 6$ 的各一个，因此样例输出即为所求答案。</p>

# 限制与约定


<p>对于 10% 的数据，$n, l, r \le 1000$。</p>
<p>对于 20% 的数据，$n, l, r \le 100000$。</p>
<p>对于另外 20% 的数据，$r - l \le 10000$。</p>
<p>对于另外 30% 的数据，$p \le 1000$，且某些数据点中 $p \le 100$。</p>
<p>对于 100% 的数据，$p \le 30000$，$l, r, n \le 10^{30}$。</p>
<p>此外为了照顾被卡常数的同学，本题存在过渡数据。为了照顾不知道高精度的小朋友，在各种类型的数据中均分布有一些 $l, r, n \le 10^{18}$ 的数据。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>matthew99</p>

# 题解


<p><a href="https://matthew99.blog.uoj.ac/blog/240">https://matthew99.blog.uoj.ac/blog/240</a></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=86">样例数据下载</a></p>
