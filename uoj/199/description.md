# 题目描述

<p>小 P 来到了 NOIP2044 的赛场上，他发现第二题的题目是这样的：给你一个长度为 $n$ 的字符串，该字符串由至多 $m$ 种不同的字符组成，其中第 $i$ 种字符的出现次数不超过 $c_i$，问你这个字符串的后缀数组是什么。</p>
<p>聪明的小 P 想到了一个新的问题希望你来帮忙解答：在题目给定的限制下，能有多少种不同的答案。也就是所有由 $m$ 种字符组成，其中第 $i$ 种字符出现次数不超过 $c_i$，且长度为 $n$ 的字符串，共有多少种不同的后缀数组。</p>
<p>由于答案很大，你只用输出答案对 $10^9+7$ 取模后的数。</p>
<p>对于一个字符串 $s=s_1s_2...s_n$，记 $\mathrm{suf}(i)$ 表示 $i$ 这个位置到末尾的子串。后缀数组为一个 $1$ 到 $n$ 的排列 $p_1,p_2,...,p_n$，满足 $\mathrm{suf}(p_1)&lt; \mathrm{suf}(p_2)&lt; \dots &lt; \mathrm{suf}(p_n)$。对于两个字符串 $s$ 和 $t$，令 $i$ 为第一个使得 $s_i \neq t_i$ 的位置，那么我们 $s_i$ 和 $t_i$ 中小的对应的字符串更小，如果 $i$ 不存在，那么长度小的字符串更小。</p>
<p>对于字符串之间的大小关系，我们规定第 $1$ 个字符最小，第 $2$ 个字符次小，以此类推。</p>

# 输入格式


<p>输入的第一行包含两个正整数 $n,m$，表示字符串的长度为 $n$，共有 $m$ 种字符。</p>
<p>接下来一行，包含 $m$ 个非负整数 $c_1,c_2,...,c_m$，表示每种字符最多的出现次数。保证 $0 \leq c_1,c_2,...,c_m \leq n,c_1+c_2+...+c_m \geq n$。</p>

# 输出格式


<p>输出共一行，包含一个正数，表示答案。</p>

# 样例一


<h4>input</h4>
<pre>3 2
2 2

</pre>

<h4>output</h4>
<pre>5

</pre>

<h4>explanation</h4>
<p>我们记 $a$ 为第一种字符，$b$ 为第二种字符，那么共有 $aab,aba,abb,baa,bab,bba$ 这六种可能的字符串。它们的后缀数组为
\begin{equation}
(1,2,3),(3,1,2),(1,3,2),(3,2,1),(2,3,1),(3,2,1).
\end{equation}
所以共有 $5$ 种不同的结果。</p>

# 样例二


<h4>input</h4>
<pre>10 5
2 3 4 3 2

</pre>

<h4>output</h4>
<pre>1003811

</pre>


# 样例三


<p>见样例数据下载</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td>$\leq 6$</td><td>$\leq 6$</td><td rowspan="4">无</td></tr><tr><td>2-3</td><td>$\leq 10$</td><td>$\leq 10$</td></tr><tr><td>4</td><td rowspan="3">$\leq 500$</td><td>$=2$</td></tr><tr><td>5</td><td>$=3$</td></tr><tr><td>6-7</td><td>$\leq 500$</td><td>$c_1=c_2=...=c_m=n$</td></tr><tr><td>8-10</td><td>$\leq 50$</td><td>$\leq 50$</td><td rowspan="3">无</td></tr><tr><td>11-14</td><td>$\leq 200$</td><td>$\leq 200$</td></tr><tr><td>15-20</td><td>$\leq 500$</td><td>$\leq 500$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$5\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=199">样例数据下载</a></p>
