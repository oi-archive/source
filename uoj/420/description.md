# 题目描述

<p><strong>本题中约定 $0^0 = 1$。</strong></p>
<p>Snuke 使用动态规划解决了一道题目。具体来说，她设计了如下递推式：
$$
F(i, j) =
\begin{cases}
  0, &amp; \text{if $i = 0$;} \\
  f_i, &amp; \text{if $i &gt; 0$ and $j = 0$;} \\
  aF(i - 1, j) + bF(i, j - 1) + c, &amp; \text{if $i &gt; 0$ and $j &gt; 0$.}
\end{cases}
$$
其中 $i, j$ 是非负整数，$a, b, c$ 是给定的常数，$f_i$ 是给定的数列。</p>
<p>Snuke 需要求出 $F(n, m)$，所以她对于 $1 \le i \le n, 1 \le j \le m$ 计算了 $F(i, j)$，这些值形成了一个 $n \times m$ 的矩阵。</p>
<p>Takahashi 希望你告诉她这个矩阵。为了避免过多的输出，你只需要输出这个矩阵的哈希值。</p>
<p>具体来说，给定整数 $h$ 和质数 $p$，你需要输出
$$
\left(
\sum_{i = 1}^{n} \sum_{j = 1}^{m} F(i, j) \, h^{(i - 1)m + (j - 1)}
\right) \bmod p
$$
的值。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行输入一个整数 $T$，表示子任务编号。</p>
<p>第二行输入四个整数 $n, m, h, p$。</p>
<p>第三行输入三个整数 $a, b, c$。</p>
<p>第四行输入 $n$ 个整数 $f_1, \ldots, f_n$。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出一行，包含一个整数，表示矩阵的哈希值。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">1
2 2 2 998244353
2 1 1
0 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">93</code></pre>
<h4>explanation</h4>
<p>题目描述中提到的矩阵是 $\left( \begin{matrix} 1 &amp; 2 \\ 4 &amp; 9 \end{matrix} \right)$，其哈希值为
$$
1 \times 2^0 + 2 \times 2^1 + 4 \times 2^2 + 9 \times 2^3 = 93.
$$</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">2
9 100000 5 998244353
5 4 7
6 5 6 9 3 7 4 5 2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">623270548</code></pre>

# 样例三


<h4>input</h4>
<pre><code class="sh_plain">3
9 1000000000 5 235497281
5 0 7
6 5 6 9 3 7 4 5 2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">211538270</code></pre>

# 限制及约定


<p>对于所有数据，保证：</p>
<ul><li>$1 \le n \le 10^6$</li>
<li>$1 \le m \le 10^9$</li>
<li>$10^8 \le p \le 10^9$，$p$ 是质数</li>
<li>$0 \le h, a, b, c, f_i &lt; p$</li>
</ul><div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">子任务编号</th><th rowspan="1">$n \le$</th><th rowspan="1">$m \le$</th><th rowspan="1">特殊性质</th><th rowspan="1">分值</th><th rowspan="1">依赖的子任务</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$1000$</td><td rowspan="1">$1000$</td><td rowspan="2">$p = 998244353$</td><td rowspan="1">5</td><td rowspan="1">无</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$10^5$</td><td rowspan="1">$10^5$</td><td rowspan="1">24</td><td rowspan="1">1</td></tr><tr><td rowspan="1">3</td><td rowspan="4">$10^6$</td><td rowspan="4">$10^9$</td><td rowspan="1">$b = 0$</td><td rowspan="1">10</td><td rowspan="3">无</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$c = 0$</td><td rowspan="1">28</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$f_i = 0$</td><td rowspan="1">30</td></tr><tr><td rowspan="1">6</td><td rowspan="1">无</td><td rowspan="1">3</td><td rowspan="1">1, 2, 3, 4, 5</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=420">样例数据下载</a></p>
