# 题目描述

<p>琪琪gaygay的假老师与gay里gay气的稳爷爷相依为gay，但自从假老师接了UOJ管理员的锅，造题的任务便一个接着一个，由于UOJ审题工作十分繁重，假老师常常累的意识模糊，这让稳爷爷十分担心。</p>
<p>经过长期的观察，稳爷爷发现假老师每天会恰好审 $k$ 道题。假设现在UOJ有 $n$ 道题要审（编号为 $1, \dots, n$），为了让审题工作更加细致，假老师会选择这样一种方式审题：</p>
<ul><li>第一天审编号为 $1, \dots, k$ 的题，</li>
<li>第二天审编号为 $2, \dots, k+1$ 的题，</li>
<li>……</li>
<li>第 $n-k+1$ 审编号为 $n-k+1, \dots, n$ 的题。</li>
</ul><p>稳爷爷接着还发现，假老师每天审题的劳累度跟当天审的 $k$ 道题中最难的题有关。每道题都有一个难度系数，是一个介于 $1$ 到 $n$ 之间的整数。假老师对于不同难度的题有不同的劳累度，可用一组常数 $w_1, \dots, w_n$ 表示。若假老师某一天审的题中难度系数的最大值为 $d$，则假老师这一天的劳累度为 $w_d$（由于假老师对题目难度有独特的口味，$w_d$ 并不一定是单调递减的）</p>
<p>假老师 $n-k+1$ 天的审题工作总劳累度定义为每一天劳累度的<strong>乘积</strong>。</p>
<p>然而作为UOJ工作人员，假老师自然不能透露任何难度信息，所以稳爷爷只好认为每道题的难度在 $1, \dots, n$ 中均匀随机，而他想知道的就是假老师总劳累度的期望值。</p>
<p>显然这个期望值 $E$ 乘以 $n^n$ 一定是一个整数，所以你只需要输出 $n^n E$ 对 $998244353$ 取模的结果即可。</p>

# 输入格式


<p>第一行两个正整数 $n,k$ 意义如题目所述。</p>
<p>第二行 $n$ 个整数表示 $w_1, \dots, w_n$。</p>

# 输出格式


<p>输出一行一个整数，表示 $n^n E$ 对 $998244353$ 取模的结果。</p>

# 样例一


<h4>input</h4>
<pre>2 2
1 2

</pre>

<h4>output</h4>
<pre>7

</pre>


# explanation


<p>共有 $\{1,1\},\{1,2\}, \{2,1\}, \{2,2\}$ 四种难度组合，劳累度期望为为 $\frac{7}{4}$。</p>

# 样例二


<h4>input</h4>
<pre>5 3
2 4 1 3 5

</pre>

<h4>output</h4>
<pre>190493

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>本题采用捆绑评测，对于一个子任务，只有通过其中所有的数据才可以获得分数。</p>
<p>对于全部数据，$1 \leq k \leq n \leq 400, 0 \leq w_i &lt; 998244353$。</p>
<p>各个测试点限制见下表：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>限制</th>
</tr></thead><tbody><tr><td>1</td><td>20</td><td>$n \leq 8$</td></tr><tr><td>2</td><td>15</td><td>$n \leq 15$</td></tr><tr><td>3</td><td>20</td><td>$n \leq 300, k \leq 2$</td></tr><tr><td>4</td><td>15</td><td>$n \leq 300, k \leq 3$</td></tr><tr><td>5</td><td>30</td><td>$n \leq 400$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=311">样例数据下载</a></p>
