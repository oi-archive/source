# 题目描述

<p>给你一个由小写拉丁字母组成的字符串 $s$。我们定义 $s$ 的一个子串的存在值为这个子串在 $s$ 中出现的次数乘以这个子串的长度。</p>
<p>对于给你的这个字符串 $s$，求所有回文子串中的最大存在值。</p>

# 输入格式


<p>一行，一个由小写拉丁字母（<samp>a</samp>~<samp>z</samp>）组成的非空字符串 $s$。</p>

# 输出格式


<p>输出一个整数，表示所有回文子串中的最大存在值。</p>

# 样例一


<h4>input</h4>
<pre>abacaba

</pre>

<h4>output</h4>
<pre>7

</pre>

<h4>explanation</h4>
<p>用 $\lvert s \rvert$ 表示字符串 $s$ 的长度。</p>
<p>一个字符串 $s_1 s_2 \dots s_{\lvert s \rvert}$ 的子串是一个非空字符串 $s_i s_{i+1} \dots s_j$，其中 $1 \leq i \leq j \leq \lvert s \rvert$。每个字符串都是自己的子串。</p>
<p>一个字符串被称作回文串当且仅当这个字符串从左往右读和从右往左读都是相同的。</p>
<p>这个样例中，有 $7$ 个回文子串 <samp>a</samp>，<samp>b</samp>，<samp>c</samp>，<samp>aba</samp>，<samp>aca</samp>，<samp>bacab</samp>，<samp>abacaba</samp>。他们的存在值分别为 $4, 2, 1, 6, 3, 5, 7$。</p>
<p>所以回文子串中最大的存在值为 $7$。</p>

# 样例二


<h4>input</h4>
<pre>www

</pre>

<h4>output</h4>
<pre>4

</pre>


# 限制与约定


<p>第一个子任务共 8 分，满足 $1 \leq \lvert s \rvert \leq 100$。</p>
<p>第二个子任务共 15 分，满足 $1 \leq \lvert s \rvert \leq 1000$。</p>
<p>第三个子任务共 24 分，满足 $1 \leq \lvert s \rvert \leq 10000$。</p>
<p>第四个子任务共 26 分，满足 $1 \leq \lvert s \rvert \leq 100000$。</p>
<p>第五个子任务共 27 分，满足 $1 \leq \lvert s \rvert \leq 300000$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=103">样例数据下载</a></p>
