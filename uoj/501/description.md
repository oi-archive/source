# 题目描述

<p>给定长度为 $2N$ 的两个正整数序列$A,B$</p>
<p>构造一个长度为 $2N$ 的序列 $C$ 。使得其满足：</p>
<ul><li>序列 $C$ 的第 $i$ 个数 $C_i$ ，只能从 $A_i$ 和 $B_i$ 中选取。即 $C_i=A_i$ 或 $C_i=B_i$。</li>
<li>设 $a$ 为序列 $A_i$ 中元素被选取的次数，$b$ 为序列 $B$ 中元素被选取的次数，则 $a=b=N$ 。注意当$C_i=A_i=B_i$时，可以认为从$A$中选取，也可以认为从$B$中选取</li>
<li>对于 $1 \le i &lt; 2N$ ,满足 $C_i \le C_{i+1}$。</li>
</ul><p>如有多解，任意输出一组解即可。</p>

# 输入格式


<p>第一行一个正整数$N$。</p>
<p>第二行$2N$个正整数数，第$i$个正整数表示$A_i$。</p>
<p>第三行$2N$个正整数数，第$i$个正整数表示$B_i$。</p>

# 输出格式


<p>若不存在解，输出-1。</p>
<p>否则一个长度为$2N$的仅包含&#39;A&#39;,&#39;B&#39;的字符串，若第i个字符为&#39;A&#39;,则$C_i=A_i$，否则$C_i=B_i$。</p>

# 样例1


<h4>input</h4>
<pre><code class="sh_plain">3
2 5 4 9 15 11
6 7 6 8 12 14</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">AABABB</code></pre>
<h4>explanation</h4>
<p>序列$C={2,5,6,9,12,14}$。可以验证$C$满足所有条件。</p>

# 样例2


<h4>input</h4>
<pre><code class="sh_plain">2
1 4 10 20
3 5 8 13</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">BBAA</code></pre>
<h4>explanation</h4>
<p>注意“AABB”也是一组合法的解。</p>

# 样例3


<h4>input</h4>
<pre><code class="sh_plain">2
3 4 5 6
10 9 8 7</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">-1</code></pre>

# 样例4


<h4>input</h4>
<pre><code class="sh_plain">6
25 18 40 37 29 95 41 53 39 69 61 90
14 18 22 28 18 30 32 32 63 58 71 78</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">BABBABAABABA</code></pre>

# 数据范围


<p>子任务1($11$分):$N \leq 2000$。</p>
<p>子任务2($89$分):$N \leq 500000$。</p>
<p>对于所有测试数据，满足$1 \leq N \leq 500000,1 \leq A_i,B_i \leq 10^9$。</p>
<p>时间限制:$\texttt{1s}$</p>
<p>空间限制:$\texttt{512MB}$</p>
