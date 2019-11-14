# 题目描述

<p>给定正整数 $n, r$，求</p>
<div style="font-size:200%;">
\begin{equation}
\sum_{d = 1}^{n}{(-1)^{\left\lfloor \sqrt{d~\times~r~\times~d} \right\rfloor}}
\end{equation}
</div>


# 输入格式


<p>第一行一个数 $T$，表示有 $T$ 组测试数据。</p>
<p>接下来 $T$ 行，每行两个正整数 $n, r$。</p>

# 输出格式


<p>输出 $T$ 行，每行一个整数表示答案。</p>

# 样例一


<h4>input</h4>
<pre>3
3 5
3 6
3 7

</pre>

<h4>output</h4>
<pre>3
1
-1

</pre>


# 限制与约定


<p>对于 30% 的数据，满足 $n \leq 10^5, r \leq 10^2, T \leq 10$；</p>
<p>对于 60% 的数据，满足 $n \leq 10^7, r \leq 10^3, T \leq 10^2$；</p>
<p>对于 100% 的数据，满足 $n \leq 10^9, r \leq 10^4, T \leq 10^4$。</p>
<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 来源


<p>中国国家队清华集训2014~2015 Day 3 - By 罗雨屏</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=42">样例数据下载</a></p>
