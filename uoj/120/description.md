# 题目描述

<p>最终，你以语文作文跑题结束了你的高考生涯，你只能回去搞OI了。</p>
<p>这就是你的宿命吗？</p>
<p>每个人都有自己的宿命，可以用一个次数不超过 $n$ 的多项式 $f(x) = \sum_{k = 0}^{n} a_k x^k$ 来描述，其中 $a_0, \dots, a_n$ 都是整数。假设你一共参加了 $n + 1$ 次影响你人生的考试，那么每一次考试的排名分别为 $f(0), f(1), \dots, f(n)$。</p>
<p>有 $n + 1$ 个正整数 $c_0, c_1, \dots, c_n$，如果对于每个 $0 \leq i \leq n$ 均满足 $1 \leq f(i) \leq c_i$，那么就称这个宿命多项式为成功的。</p>
<p>现在给你 $n$ 和 $c_0, c_1, \dots, c_n$，求有多少个成功的宿命多项式。你只用输出答案对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）取模后的值。</p>

# 输入格式


<p>第一行一个正整数 $q$，表示有 $q$ 组询问。</p>
<p>接下来 $q$ 行，每行表示一组询问。第一个数为正整数 $n$，后面跟着 $n + 1$ 个正整数 $c_0, c_1, \dots, c_n$，整数间均用一个空格分隔。</p>

# 输出格式


<p>对每组询问输出一行，表示相应的答案。</p>

# 样例一


<h4>input</h4>
<pre>4
1 2 5
1 12345 67890
2 1 2 3
2 123 456 789

</pre>

<h4>output</h4>
<pre>10
838102050
4
22126944

</pre>

<h4>explanation</h4>
<p>对于样例一的第 $3$ 个询问，$4$ 个成功的宿命多项式分别为：</p>
<ol><li>$f(x)=1$</li>
<li>$f(x)=x+1$</li>
<li>$f(x)=-x^2+2x+1$</li>
<li>$f(x)=x^2-x+1$</li>
</ol>
# 样例二


<h4>input</h4>
<pre>2
4 3 3 3 3 3
4 10000 20000 30000 40000 50000

</pre>

<h4>output</h4>
<pre>3
68284084

</pre>


# 样例三


<h4>input</h4>
<pre>1
6 192837465 123456789 987654321 147258369 963852741 543219876 987651234

</pre>

<h4>output</h4>
<pre>470636264

</pre>


# 限制与约定


<p>对于所有数据，$q \leq 10$，$1 \leq c_0, \dots, c_n \leq 10^9$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td>$n \leq 1$</td><td>无</td></tr><tr><td>2</td><td rowspan="2">$n \leq 2$</td><td>$c_0, \dots, c_n \leq 10^5$</td></tr><tr><td>3</td><td rowspan="6">无</td></tr><tr><td>4</td><td>$n \leq 3$</td></tr><tr><td>5</td><td rowspan="2">$n \leq 4$</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="2">$n \leq 5$</td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="2">$n \leq 6$</td><td>$q = 1$</td></tr><tr><td>10</td><td>无</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=120">样例数据下载</a></p>
