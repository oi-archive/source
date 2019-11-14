# 题目描述

<p>有两个仅包含小写英文字母的字符串 $A$ 和 $B$。</p>
<p>现在要从字符串 $A$ 中取出 $k$ 个<strong>互不重叠</strong>的非空子串，然后把这 $k$ 个子串按照其在字符串 $A$ 中出现的顺序依次连接起来得到一个新的字符串。请问有多少种方案可以使得这个新串与字符串 $B$ 相等？</p>
<p>注意：子串取出的位置不同也认为是不同的方案。</p>

# 输入格式


<p>第一行是三个正整数 $n,m,k$，分别表示字符串 $A$ 的长度，字符串 $B$ 的长度，以及问题描述中所提到的 $k$，每两个整数之间用一个空格隔开。</p>
<p>第二行包含一个长度为 $n$ 的字符串，表示字符串 $A$。</p>
<p>第三行包含一个长度为 $m$ 的字符串，表示字符串 $B$。</p>

# 输出格式


<p>输出共一行，包含一个整数，表示所求方案数。 </p>
<p><strong>由于答案可能很大，所以这里要求输出答案对 $1000000007$ 取模的结果。</strong></p>

# 样例一


<h4>input</h4>
<pre>6 3 1
aabaab
aab

</pre>

<h4>output</h4>
<pre>2

</pre>


# 样例二


<h4>input</h4>
<pre>6 3 2
aabaab
aab

</pre>

<h4>output</h4>
<pre>7

</pre>


# 样例三


<h4>input</h4>
<pre>6 3 3
aabaab
aab

</pre>

<h4>output</h4>
<pre>7

</pre>

<h4>explanation</h4>
<p>所有合法方案如下：（加下划线的部分表示取出的子串）</p>
<p>样例一：<samp><strong><u>aab</u></strong> aab / aab <strong><u>aab</u></strong></samp></p>
<p>样例二：<samp><strong><u>a</u> <u>ab</u></strong> aab / <strong><u>a</u></strong> aba <strong><u>ab</u></strong> / a <strong><u>a</u></strong> ba <strong><u>ab</u></strong> / aab <strong><u>a</u> <u>ab</u></strong> / <strong><u>aa</u> <u>b</u></strong> aab / <strong><u>aa</u></strong> baa <strong><u>b</u></strong> / aab <strong><u>aa</u> <u>b</u></strong></samp></p>
<p>样例三：<samp><strong><u>a</u> <u>a</u> <u>b</u></strong> aab / <strong><u>a</u> <u>a</u></strong> baa <strong><u>b</u></strong> / <strong><u>a</u></strong> ab <strong><u>a</u></strong> a <strong><u>b</u></strong> / <strong><u>a</u></strong> aba <strong><u>a</u> <u>b</u></strong> / a <strong><u>a</u></strong> b <strong><u>a</u></strong> a <strong><u>b</u></strong> / a <strong><u>a</u></strong> ba <strong><u>a</u> <u>b</u></strong> / aab <strong><u>a</u> <u>a</u> <u>b</u></strong></samp></p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>$m$的规模</th>
<th>$k$的规模</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="7">$n \leq 500$</td><td rowspan="7"> $m \leq 50$</td><td>$k=1$</td></tr><tr><td>2</td><td rowspan="2">$k=2$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">$k=m$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$k \leq m$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n \leq 1000$</td><td rowspan="2">$m \leq 100$</td></tr><tr><td>9</td></tr><tr><td>10</td><td>$m \leq 200$</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$128\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=149">样例数据下载</a></p>
