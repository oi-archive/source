# 题目描述

<p>“又要出题了。” 宇宙出题中心主任 —— 吉米多出题斯基，坐在办公桌前策划即将到来的 UOI。</p>
<p>这场比赛有 $n$ 道题，吉米多出题斯基需要决定这些题目的难度，然后再在汪洋大海中寻找符合该难度的题目。</p>
<p>题目的难度可以用一个 $1$ 到 $n$ 的<strong>排列</strong> $a_1, \dots, a_n$ 表示，其中 $a_i$ 表示第 $i$ 道题目在这 $n$ 道题目中是第 $a_i$ 简单的题目，即恰有 $a_i - 1$ 道题目比第 $i$ 道题目简单。</p>
<p>经验丰富的吉米多出题斯基早就悟出了一种科学地决定难度顺序的方法。首先，吉米多出题斯基定义了难度递增子序列为序列 $a_{p_1}, a_{p_2}, \dots, a_{p_k}$ （$1 \le p_1 &lt; p_2 &lt; \dots &lt; p_k \le n$） 满足 $a_{p_1} &lt; a_{p_2} &lt; \dots &lt; a_{p_k}$ 。然后，吉米多出题斯基决定了 $n$ 个整数 $f_1, \dots, f_n$，他希望找出一个难度顺序使得对于每个 $1 \le i \le n$ 均满足以 $a_i$ 结尾的难度递增子序列的最长长度恰好为 $f_i$。</p>
<p>但吉米多出题斯基日理万机，于是他找到了你 —— 风璃殇做不出题耶维奇，请你帮助吉米多出题斯基构造一个符合条件的 $a_1, \dots, a_n$ 吧！</p>

# 输入


<p>第一行一个正整数 $n$。</p>
<p>接下来一行 $n$ 个数，其中第 $i$ 个数表示 $f_i$。（$1 \le f_i \le n$）</p>

# 输出


<p>输出一行 $n$ 个数，表示 $a_1, \dots, a_n$。</p>
<p>题目保证至少存在一组解。如有多组解，输出任意一组均可。</p>

# 样例一


<h4>input</h4>
<pre>7
1 1 1 1 1 1 1

</pre>

<h4>output</h4>
<pre>7 6 5 4 3 2 1

</pre>

<h4>explanation</h4>
<p>以每个 $a_i$ 结尾的最长难度递增子序列分别为 $\{7\}, \{6\}, \{5\}, \{4\}, \{3\}, \{2\}, \{1\}$。</p>

# 样例二


<h4>input</h4>
<pre>7
1 2 3 2 4 4 3

</pre>

<h4>output</h4>
<pre>1 4 5 2 7 6 3

</pre>

<h4>explanation</h4>
<p>以每个 $a_i$ 结尾的最长难度递增子序列分别为 $\{1\}, \{1, 4\}, \{1, 4, 5\}, \{1, 2\}, \{1, 4, 5, 7\}, \{1, 4, 5, 6\}, \{1, 2, 3\}$。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="3">$\le 10$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$\le 1000$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$\le 10^5$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=278">样例数据下载</a></p>
