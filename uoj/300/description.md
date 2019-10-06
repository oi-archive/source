# 题目描述

<p>简单的题目，既是礼物，也是毒药。</p>
<p>B 君设计了一道简单的题目，准备作为 gift 送给大家。</p>
<p>输入一个长度为 $n$ 的数列 $a_1, a_2, \ldots, a_n$</p>
<p>问有多少个长度大于等于 $2$ 的不上升的子序列 $a_{b_1}, a_{b_2}, \ldots ,a_{b_k}$ 满足</p>
<p>$$\prod_{i = 2}^k \binom{a_{b_{i-1}}}{a_{b_i}} \bmod 2= \binom{a_{b_1}}{a_{b_2}} \times \binom{a_{b_2}}{a_{b_3}} \times \cdots \times \binom{a_{b_{k-1}}}{a_{b_k}} \bmod 2 &gt; 0$$</p>
<p>输出这个个数对 $1000000007$ 取模的结果。</p>
<p>G 君看到题目后，为大家解释了一些基本概念。</p>
<p>我们选择任意多个整数 $b_i$ 满足</p>
<p>$$1 \leq b_1 &lt; b_2 &lt; \cdots &lt; b_{k-1} &lt; b_{k} \leq n$$</p>
<p>我们称 $a_{b_1}, a_{b_2}, \ldots ,a_{b_k}$ 是 $a$ 的一个子序列。</p>
<p>如果这个子序列同时还满足</p>
<p>$$a_{b_1} \geq a_{b_2} \geq \cdots \geq a_{b_{k-1}} \geq a_{b_{k}}$$</p>
<p>我们称这个子序列是不上升的。</p>
<p>组合数 $\binom{n}{m}$ 是从 $n$ 个互不相同的元素中取 $m$ 个元素的方案数，具体计算方法如下：</p>
<p>$$\binom{n}{m} = \frac{n!}{m!(n-m)!} = \frac{n \times (n - 1) \times \cdots \times 2 \times 1}{(m \times (m - 1) \times \cdots \times 2 \times 1)((n-m) \times (n-m - 1) \times \cdots \times 2 \times 1)}$$</p>
<p>这里要特别注意，因为我们只考虑不上升子序列，所以在求组合数的过程中，一定满足 $n \geq m$，也就是 $\binom{a_{b_{i-1}}}{a_{b_{i}}}$ 中一定有 $a_{b_{i-1}} \geq a_{b_{i}}$。</p>
<p>我们在这里强调取模 $x \bmod y$ 的定义：</p>
<p>$$x \bmod y = x - \left \lfloor \frac{x}{y} \right \rfloor \times y$$</p>
<p>其中 $\lfloor n \rfloor$ 表示小于等于 $n$ 的最大整数。</p>
<p>$x \bmod 2 &gt; 0$，就是在说$x$是奇数。</p>
<p>与此同时，经验告诉我们一个长度为 $n$ 的序列，子序列个数有 $O(2^n)$ 个，所以我们通过对答案取模来避免输出过大。</p>
<p>B 君觉得 G 君说的十分有道理，于是再次强调了这些基本概念。</p>
<p>最后，G 君听说这个题是作为 gift 送给大家，她有一句忠告。</p>
<p>&#34;Vorsicht, Gift!&#34;</p>
<p>“小心……剧毒！”</p>

# 输入格式


<p>第一行一个整数$n$。</p>
<p>接下来$n$行，每行一个整数，这$n$行中的第$i$行，表示$a_i$。</p>

# 输出格式


<p>一行一个整数表示答案。</p>

# 样例一


<h4>input</h4>
<pre>4
15
7
3
1

</pre>

<h4>output</h4>
<pre>11

</pre>


# 样例二至样例九


<p>见样例数据下载。</p>

# 限制与约定


<ul><li>对于前 $10\%$ 的测试点，$n \leq 9, 1 \leq a_i \leq 13$；</li>
<li>对于前 $20\%$ 的测试点，$n \leq 17, 1 \leq a_i \leq 20$；</li>
<li>对于前 $40\%$ 的测试点，$n \leq 1911, 1 \leq a_i \leq 4000$；</li>
<li>对于前 $70\%$ 的测试点，$n \leq 2017$；</li>
<li>对于前 $85\%$ 的测试点，$n \leq 100084$；</li>
<li>对于 $100\%$ 的测试点， $1 \leq n \leq 211985, 1 \leq a_i \leq 233333$。所有的$a_i$互不相同，也就是说不存在$i, j$同时满足$1 \leq i &lt; j \leq n$和$a_i = a_j$。</li>
</ul><p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=300">样例数据下载</a></p>
