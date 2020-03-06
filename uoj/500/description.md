# 题目描述

<p>给定 $n$ 次多项式</p>
<p>\begin{equation}
f(x) = \sum_{i=0}^{n} a_ix^i
\end{equation}</p>
<p>$Q$ 次询问，第 $i$ 次询问 $f(q_i)$ 对 $998244353$ 取模的值。</p>

# 输入格式


<p><strong>由于本题的数据范围较大，所有测试点的</strong> $q_i$ <strong>将在程序内生成。</strong></p>
<p>第一行两个整数 $n,Q$。$n,Q$ 的意义见题目描述。</p>
<p>第二行 $n+1$ 个整数，第 $i$ 个整数表示 $a_{i-1}$</p>
<p>第三行三个整数 $q_0,q_{\mathrm{x}},q_{\mathrm{y}}$，表示 $q_i$ 的生成方式。</p>
<p>$q_i$ 按照如下规则生成:</p>
<p>$\forall 1 \leq i \leq Q,q_i=(q_{i-1} \times q_{\mathrm{x}}+q_{\mathrm{y}})\bmod 998244353$</p>

# 输出格式


<p>由于输出规模过大，你只需要输出所有询问答案取完模之后的 $\mathbin{\mathrm{xor}}$ 和即可。</p>

# 样例一


<h4>input</h4>
<pre>2 2
1 2 3
1 2 1

</pre>

<h4>output</h4>
<pre>128

</pre>

<h4>explanation</h4>
<p>$q_1=2 \times q_0 +1=3$</p>
<p>$q_2=2 \times q_1 +1=7$</p>
<p>答案 $=(1+2 \times 3+ 3 \times 3^2) \mathbin{\mathrm{xor}} (1+2 \times 7+3 \times 7^2)=34 \mathbin{\mathrm{xor}} 162=128$</p>

# 样例二


<p>见样例数据下载</p>

# 数据范围


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试包编号</th><th>$n\leq $</th><th>$Q \leq$</th><th>$特殊性质 $</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$1000$</td><td>$1000$</td><td rowspan="3">无</td><td>$5$</td></tr><tr><td>$2$</td><td>$10^5$</td><td>$10^5$</td><td>$15$</td></tr><tr><td>$3$</td><td rowspan="4">$2.5 \times 10^5$</td><td>$2.5 \times 10^5$</td><td>$15$</td></tr><tr><td>$4$</td><td rowspan="2">$5 \times 10^5$</td><td>$q_{\mathrm{y}}=0$</td><td>$25$</td></tr><tr><td>$5$</td><td rowspan="2">无</td><td>$25$</td></tr><tr><td>$6$</td><td>$10^6$</td><td>$15$</td></tr></tbody></table></div>

<p>对于所有测试数据，满足 $1 \leq n \leq 2.5 \times 10^5, 1 \leq Q \leq 10^6, 2 \leq q_{\mathrm{x}} &lt; 998244353, 0 \leq q_0,q_{\mathrm{y}} &lt; 998244353$。</p>
<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=500">样例数据下载</a></p>
