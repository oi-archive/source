# 题目描述

<div class="hide">
$\newcommand\xor{\mathbin{\mathrm{xor}}}$
</div>

<p>我有一个数列 $a_1, a_2, \dots, a_n$，每个 $a_i$ 都是小于 $2^m$ 的非负整数。</p>
<p>现在请您实现三种操作，格式说明如下：</p>
<ul><li>$1$ $x$ $y$ $w$：对于所有 $x \leq i \leq y$，将 $a_i$ 修改为 $a_i \xor w$。其中 $w$ 是一个小于 $2^m$ 的非负整数。</li>
<li>$2$ $x$ $y$ $w$：对于所有 $x \leq i \leq y$，将 $a_i$ 修改为 $w$。其中 $w$ 是一个小于 $2^m$ 的非负整数。</li>
<li>$3$：从 $a_1, a_2, \dots, a_n$ 中选出若干个数，使得选出的数异或和最大。请输出这个最大值。</li>
</ul><p>这里 $\xor$ 表示按位异或运算，$x_1, x_2, \dots, x_l$ 的异或和是指 $x_1 \xor x_2 \xor \dots \xor x_l$。</p>

# 输入格式


<p>第一行三个正整数 $n,m,q$。</p>
<p>接下来 $n$ 行为初始时 $a_1, a_2, \dots, a_n$ 的值。</p>
<p>接下来 $q$ 行，每行表示一个操作。操作的格式如前所述。保证 $1 \leq x \leq y \leq n$。</p>
<p>$a_1, \dots, a_n$ 和 $w$ 均用恰好 $m$ 位的 01 串表示这个数的二进制表示。左边是最高位，右边是最低位，不足 $m$ 位的在左边补 $0$。</p>

# 输出格式


<p>对于每个 $3$ 号操作，输出一个 $m$ 位 01 串表示答案的二进制表示。</p>

# 样例一


<h4>input</h4>
<pre>3 4 7
0000
0011
0110
3
1 2 3 0010
3
2 1 2 0010
3
2 1 3 0000
3

</pre>

<h4>output</h4>
<pre>0110
0101
0110
0000

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$q$</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td>$= 10$</td><td>$= 10$</td><td>$= 1000$</td><td rowspan="4">无</td></tr><tr><td>2</td><td>$= 500$</td><td>$= 500$</td><td>$= 10$</td></tr><tr><td>3</td><td>$= 120$</td><td>$= 120$</td><td>$= 120$</td></tr><tr><td>4</td><td>$= 2000$</td><td>$= 2000$</td><td>$= 10$</td></tr><tr><td>5</td><td rowspan="3">$= 1800$</td><td rowspan="3">$= 1800$</td><td rowspan="3">$= 1800$</td><td>$1, 2$ 操作中 $x = y$</td></tr><tr><td>6</td><td>只有 $1, 3$ 操作</td></tr><tr><td>7</td><td>只有 $2, 3$ 操作</td></tr><tr><td>8</td><td>$=1500$</td><td>$=1500$</td><td>$=1500$</td><td rowspan="3">无</td></tr><tr><td>9</td><td>$=1800$</td><td>$=1800$</td><td>$=1800$</td></tr><tr><td>10</td><td>$=2000$</td><td>$=2000$</td><td>$=2000$</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>中国国家集训队互测2015 - By 金策</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=91">样例数据下载</a></p>
