# 题目描述

<p>著名核物理专家 Picks 提出了核聚变特征值这一重要概念。</p>
<p>核聚变特征值分别为 $x$ 和 $y$ 的两个原子进行核聚变，能产生数值为 $\text{sgcd}(x, y)$ 的核聚变反应强度。</p>
<p>其中， $\text{sgcd}(x, y)$ 表示 $x$ 和 $y$ 的次大公约数，即能同时整除 $x, y$ 的正整数中第二大的数。如果次大公约数不存在则说明无法核聚变， 此时 $\text{sgcd}(x, y) = -1$。</p>
<p>现在有 $n$ 个原子，核聚变特征值分别为 $a_1, a_2, \dots, a_n$。然后 Picks 又从兜里掏出一个核聚变特征值为 $a_1$ 的原子，你需要计算出这个原子与其它 $n$ 个原子分别进行核聚变反应时的核聚变反应强度，即 $\text{sgcd}(a_1, a_1), \text{sgcd}(a_1, a_2), \dots, \text{sgcd}(a_1, a_n)$。</p>

# 输入格式


<p>第一行一个正整数 $n$。</p>
<p>第二行 $n$ 个用空格隔开的正整数，第 $i$ 个为 $a_i$。</p>

# 输出格式


<p>一行 $n$ 个用空格隔开的整数，第 $i$ 个表示 $\text{sgcd}(a_1, a_i)$。</p>
<p>C/C++ 输入输出 long long 时请用 <code>%lld</code>。<strong>由于本题数据量较大，建议不要使用 cin/cout 进行输入输出。</strong></p>

# 样例一


<h4>input</h4>
<pre>4
12450 1 2 450

</pre>

<h4>output</h4>
<pre>6225 -1 1 75

</pre>


# 样例二


<h4>input</h4>
<pre>8
30030 6 10 12 55 36 450 666

</pre>

<h4>output</h4>
<pre>15015 3 5 3 11 3 15 3

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$、$a_i$的规模</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n = 1$，$a_i \le 10^9$</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="4">$n \le 10^4$，$a_i \le 10^9$</td></tr><tr><td>4</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$n \le 10^5$，$a_i \le 10^{12}$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=48">样例数据下载</a></p>
