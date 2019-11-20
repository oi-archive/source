# 题目描述

<p>2044年，Picks建成了人类第一台基于量子理论的银河系信息传递机。</p>
<p>Picks游遍了宇宙，雇用了 $n$ 个外星人来帮他作为信息传递机的中转站。我们将外星人依次编号为 $1$ 到 $n$，其中 $i$ 号外星人有 $a_i$ 根手指。</p>
<p>外星人都是很低级的，于是Picks花费了很大的精力，才教会他们学会扳手指数数。</p>
<p>Picks现在准备传递 $x$ 个脉冲信号给VFleaKing，于是他把信号发给$1$号外星人，然后$1$号外星人把信号发送给$2$号外星人，$2$号外星人把信号发送给$3$号外星人，依次类推，最后$n$号外星人把信号发给VFleaKing。</p>
<p>但是事情没有Picks想象的那么顺利，由于外星人手指个数有限，所以如果 $i$ 号外星人收到了 $t$ 个脉冲信号，他会错误的以为发送过来的是 $t \bmod a_i$ 个脉冲信号，导致只发送了 $t \bmod a_i$ 个脉冲信号出去。</p>
<p>Picks希望他发送出去的脉冲信号数量 $x$ 与VFleaKing收到的脉冲信号数量 $y$ 的差的绝对值尽量小。于是他决定通过重新排列这些外星人的顺序来达到这一目的。请你求出与 $x$ 之差最小的 $y$。除此之外，请求出有多少种排列外星人的方式能达到最优解，你只需要输出方案数对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）取模后的结果。</p>

# 输入格式


<p>第一行两个正整数$n, x$。</p>
<p>接下来一行有 $n$ 个正整数 $a_i$，表示 $i$ 号外星人的手指数。</p>

# 输出格式


<p>第一行一个整数表示最优情况下VFleaKing收到的脉冲数量。</p>
<p>第二行一个整数表示达到最优情况的方案数。</p>

# 样例一


<h4>input</h4>
<pre>2 15
7 10

</pre>

<h4>output</h4>
<pre>5
1

</pre>

<h4>explanation</h4>
<p>共两种可行方案：</p>
<ol><li>$15 \bmod 7 = 1$，$1 \bmod 10 = 1$</li>
<li>$15 \bmod 10 = 5$，$5 \bmod 7 = 5$</li>
</ol><p>显然第二种方案更优。</p>

# 样例二


<h4>input</h4>
<pre>7 33
2 4 6 8 16 16 32

</pre>

<h4>output</h4>
<pre>1
5040

</pre>

<h4>explanation</h4>
<p>每个排列方案都是最优解。</p>

# 样例三


<p>见样例数据下载</p>

# 限制与约定


<p>对于每个测试点，答对第一问可获得 40% 的分数，答对第二问可获得 60% 的分数。</p>
<p><strong>请注意你必须输出两个整数否则会判0分。</strong>假如你只做了第一问，那么你应该输出你第一问的答案，然后再随便输出一个第二问的答案。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>$x$ 和 $a_i$的规模</th>
</tr></thead><tbody><tr><td>1</td><td>$n \leq 10$</td><td>$x, a_i \leq 20$</td></tr><tr><td>2</td><td rowspan="2">$n \leq 50$</td><td rowspan="2">$x, a_i \leq 100$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$n \leq 100$</td><td rowspan="3">$x, a_i \leq 500$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$n \leq 1000$</td><td rowspan="4">$x, a_i \leq 5000$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=22">样例数据下载</a></p>
