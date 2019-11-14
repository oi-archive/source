# 题目描述

<p>给你一个长度为 $n$ 的字符串 $S$，你需要将其划分成若干个不相交的非空连续子串 $s_1,s_2, ... , s_k(k \ge 1)$，满足：</p>
<ul><li>每个子串 $s_i(1 \le i \le k)$ 是<strong>不循环</strong>的。</li>
<li>相邻的两个子串不同。即 $s_i \neq s_{i+1} (1\le i \lt k)$。</li>
<li>$s_1,s_2, ... ,s_k$从左到右拼接起来恰好为原串。即$S=\overline{s_1s_2...s_k}$。</li>
</ul><p>一个字符串 $S$ 是<strong>循环</strong>的，当且仅当存在一个整数 $k(k \ge 2)$ 和一个字符串 $s$，使得 $k$ 个 $s$ 拼接起来后的字符串与 $S$ 相等。例如字符串 $S=\text{abab}$ 是循环的，因为存在 $k=2,s=\text{ab}$。一个字符串是<strong>不循环</strong>的，当且仅当它不是<strong>循环</strong>的。字符串 $\text{ababa}$ 和 $\text{abcac}$ 就是<strong>不循环</strong>的。</p>
<p>你需要计算有多少种不同的划分方法。由于方案数可能很大，你只需要输出方案数模 $998244353$ 的值。两个划分方法不同是指划分出的子串序列不同。</p>

# 输入格式


<p>输入只有一行，包含一个只由小写字母组成的字符串 $S$。</p>

# 输出格式


<p>输出一个整数，表示方案数模 $998244353$ 的值。</p>

# 样例一


<h4>input</h4>
<pre><code>ababab</code></pre>
<h4>output</h4>
<pre><code>22</code></pre>

# 样例二


<h4>input</h4>
<pre><code>abracadabracadabracadabra</code></pre>
<h4>output</h4>
<pre><code>16762880</code></pre>

# 限制与约定


<p>对于所有数据，有$|S| \le 200000$。</p>
<ul><li>子任务 $1$（$7\%$）：$|S| \le 300$。</li>
<li>子任务 $2$（$10\%$）：$|S| \le 2000$。</li>
<li>子任务 $3$（$13\%$）：$|S| \le 8000$。</li>
<li>子任务 $4$（$5\%$）：$S$ 的每个字符从指定的某个字符集中随机生成。</li>
<li>子任务 $5$（$25\%$）：保证对于 $S$ 的任意子串，要么它是不循环的，要么它的循环次数（即题面描述中的 $k$）不会超过 $10$。</li>
<li>子任务 $6$（$40\%$）：无特殊限制。</li>
</ul><p><strong>时间限制：</strong>$1\mathtt{s}$</p>
<p><strong>空间限制：</strong>$512\mathtt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=429">样例数据下载</a></p>
