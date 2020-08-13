# 题目描述

<p>出题人 02 喜欢研究己酸 $(CH_3(CH_2)_4COOH)$ 的化学性质。 </p>
<p>现在平面上有 $n$ 个己酸分子，第 $i$ 个分子位于 $(x_i,y_i)$。己酸分子非常小，因此出题人 02 将其设为了一个点。</p>
<p>出题人 02 总是在想把这些己酸集合在一起会发生什么。所以他会问你 $Q$ 个问题：第 $i$ 个问题中，他想统计出到 $(0,z_i)$ 这一点的欧几里得距离不超过 $R_i$（小于等于 $R_i$）的己酸分子个数。</p>
<p>你作为未来的大理论计算机科学家，当然知道用什么算法和数据结构来解决啦！</p>

# 输入格式


<p>第一行两个整数 $n,Q$.</p>
<p>接下来 $n$ 行，每行两个整数 $x_i,y_i$。</p>
<p>接下来 $Q$ 行，每行两个整数 $z_i,R_i$。</p>

# 输出格式


<p>$Q$ 行，第 $i$ 行一个整数表示第 $i$ 次询问的答案。</p>

# 样例一


<h4>input</h4>
<pre>5 5
-27 -18
-11 10
-29 4
26 26
16 -9
-11 22
-24 15
-19 3
-11 6
-17 24

</pre>

<h4>output</h4>
<pre>1
0
0
0
1

</pre>

<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/553/jisuan.webp" alt="样例解释"/></p>
<p><del>这个样例是随机生成的，所以看上去非常不靠谱。</del></p>

# 样例二


<p>见样例数据下载。</p>
<p>该样例数据范围同测试包 1。</p>

# 样例三


<p>见样例数据下载。</p>
<p>该样例数据满足 $x_i,y_i,z_i$ 均在 $[-10^5,10^5]$ 均匀随机生成，$R_i$ 在 $[1,10^5]$ 均匀随机生成。</p>

# 数据范围


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试包编号</th><th>$n$</th><th>$Q$</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$\le 2000$</td><td>$\le 5000$</td><td>$15$</td></tr><tr><td>$2$</td><td>$\le 12000$</td><td>$\le 5 \times 10^5$</td><td>$30$</td></tr><tr><td>$3$</td><td>$\le 4000$</td><td rowspan="3">$\le 10^6$</td><td>$20$</td></tr><tr><td>$4$</td><td>$\le 7000$</td><td>$20$</td></tr><tr><td>$5$</td><td>$\le 12000$</td><td>$15$</td></tr></tbody></table></div>

<p>对于所有测试数据，满足$1 \le n \le 12000,0 \le Q \le 10^6,|x_i|,|y_i|,|z_i| \le 10^9,1 \le R_i \le 10^9$。</p>
<p>特殊地，测试包 2 中 $x_i,y_i,z_i,R_i$ 均是在上述合法范围内均匀随机生成的。</p>
<p>极限数据输入约 $\texttt{21MB}$，输出约 $\texttt{5MB}$，请选手注意自己 IO 的用时。</p>
<p><strong>时间限制</strong>：$4\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=553">样例数据下载</a></p>
