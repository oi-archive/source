# 题目描述

<p>众所周知，小葱同学擅长计算，尤其擅长计算组合数。小葱现在希望你计算</p>
<p>$$
\left(\sum_{k=0}^n f(k) \times x^k \times \binom n k\right) \bmod p
$$</p>
<p>的值。其中 $n, x, p$ 为给定的整数，$f(k)$ 为给定的一个 $m$ 次多项式 $f(k) = a_0 + a_1 k + a_2 k^2 + \cdots + a_m k^m$。</p>
<p>$\binom n k$ 为组合数，其值为 $\binom n k = \frac{n!}{k!(n-k)!}$。</p>

# 输入格式


<p>第一行四个非负整数 $n, x, p, m$。</p>
<p>第二行 $m + 1$ 个整数，分别代表 $a_0, a_1, \cdots, a_m$。</p>

# 输出格式


<p>一行一个整数表示答案。</p>

# 样例1


<h4>input</h4>
<pre><code class="sh_plain">5 1 10007 2
0 0 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">240</code></pre>
<h4>explanation</h4>
<p>$f(0) = 0，f(1) = 1，f(2) = 4，f(3) = 9，f(4) = 16，f(5) = 25$。</p>
<p>$x = 1$，故 $x^k$ 恒为 $1$，乘积中的该项可以忽略。</p>
<p>$\binom 5 0 = 1, \binom 5 1 = 5, \binom 5 2 = 10, \binom 5 3 = 10, \binom 5 4 = 5, \binom 5 5 = 1$。</p>
<p>最终答案为：</p>
<p>$$
\sum_{k=0}^5 f(5) \times \binom 5 k = 0\times 1 + 1\times 5 + 4\times 10 + 9\times 10 + 16\times 5 + 25\times 1 = 240
$$</p>

# 样例2


<h4>input</h4>
<pre><code class="sh_plain">996 233 998244353 5
5 4 13 16 20 15</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">869469289</code></pre>

# 样例3


<p>见附加文件中 <code>ex_problem3.in</code> 与 <code>ex_problem3.ans</code>。</p>

# 数据范围


<p>对于所有测试数据：$1\le n, x, p \le 10^9, 0\le a_i\le 10^9, 0\le m \le \min(n,1000)$。</p>
<p>每个测试点的具体限制见下表：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n \le$</th><th>$m \le$</th><th>其他特殊限制</th></tr></thead><tbody><tr><td>$1 \sim 3$</td><td>$1000$</td><td>$1000$</td><td>无</td></tr><tr><td>$4 \sim 6$</td><td>$10^5$</td><td rowspan="2">$0$</td><td>$p$是质数</td></tr><tr><td>$7 \sim 8$</td><td rowspan="4">$10^9$</td><td rowspan="2">无</td></tr><tr><td>$9 \sim 12$</td><td>$5$</td></tr><tr><td>$13 \sim 16$</td><td rowspan="2">$1000$</td><td>$x=1$</td></tr><tr><td>$17 \sim 20$</td><td>无</td></tr></tbody></table></div>

<p><strong>时间限制:</strong> $1\texttt{s}$</p>
<p><strong>空间限制:</strong> $512\texttt{MB}$</p>
<p><a href="http://uoj.ac/download.php?type=problem&amp;id=540">附加数据下载</a></p>
