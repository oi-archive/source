# 题目描述

<p>九条可怜最近研究了一下多项式在系数模 $2$ 意义下的性质。她发现可以用多项式在模 $2$ 意义下的乘法得到一个很长的字符串：</p>
<p>对于一个 $n$ 次的系数为 $0$ 或 $1$ 的多项式 $f(x)$，我们在模 $2$ 意义下计算 $g(x) = f(x)^m$，则 $g(x)$ 为一个 $nm$ 次的多项式，它有 $nm + 1$ 个系数，将这些系数从<strong>高位到低位</strong>写下来，就可以得到一个长度为 $nm + 1$ 的 01 字符串。</p>
<p>例如对于多项式 $f(x) = x^3 +x+1$，计算$g(x) = f(x)^3 = x^9 +x^7 +x^6 +x^5 +x^2 +x+1$，这样我们得到了一个长度为 $10$ 的字符串 <samp>1011100111</samp>。
现在可怜有一个次数为 $n$ 的多项式 $f(x)$，整数 $m, L, R$ 以及一个长度为 $K$ 的 01 串 $t$。令 $s$ 为 $f(x)^m$ 得到的字符串，$s[L, R]$ 为 $s$ 的第 $L$ 个字符到第 $R$ 个字符，可怜想要知道 $t$ 在 $s[L, R]$ 中出现了多少次。</p>

# 输入格式


<p>第一行输入一个整数 $T$ 表示数据组数。</p>
<p>每组数据第一行输入五个整数 $n, m, K, L, R$。</p>
<p>第二行输入一个长度为 $n + 1$ 的 01 串表示多项式 $f(x)$ 的系数，其中第 $i$ 位表示 $f(x)$ 的第 $n - i + 1$ 次系数。</p>
<p>第三行输入一个长度为 $K$ 的字符串表示字符串 $t$。</p>

# 输出格式


<p>对于每组数据输出一个整数表示答案。</p>

# 样例一


<h4>input</h4>
<pre>1
3 3 2 1 10
1011
01

</pre>

<h4>output</h4>
<pre>2

</pre>


# 样例二


<h4>input</h4>
<pre>4
18 425979 3 4394755 5294599
1110011000110000001
101
18 654615 18 8371190 8974716
1110110011000010001
100011111010101011
18 509662 18 525987 5910726
1000010010001100000
010100000101010100
18 446204 18 2628281 3483268
1011011111101001001
000000000100010001

</pre>

<h4>output</h4>
<pre>84292
1367
1068
6713

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$K$</th>
<th>其他约定</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="10">$\le 18$</td><td>$\le 500$</td><td rowspan="10">18</td><td rowspan="3">无</td></tr><tr><td>2</td><td rowspan="2">$\le 2\times 10^5$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="7">$\le 10^{16}$</td><td rowspan="2">$R - L \le 10^4$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="3">$L = 1, R = nm + 1$</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="2">无</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于 100% 的数据，保证 $1 \le T \le 5，1 \le L \le R \le nm+1$。</p>
<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=292">样例数据下载</a></p>
