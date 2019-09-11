# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
在BERLAND不幸的年是这样的年，其数目$N$可以表示为$N=x^a+y^b$其中a和b都是非负整数。
</p>
<p>
例如，如果$x  = 2$和$y  = 3$，则年4和17是不幸的（$4 = 2^0  + 3^1$，$17 = 2^3  + 3^2  = 2^4  + 3^0$），年份18是幸运的，因为没有这样的表示。
</p>
<p>
这个没有不幸的岁月的这段时间称为黄金时代。
</p>
<p>
你应该写一个程序，找出黄金时代的最大长度，这段黄金年代应该开始于不早于年份l，结束于不晚于年份r 。如果区间$[l,r]$中的所有年份都不幸运，则答案为0。
</p>
<p>
<br/>
</p>
<p>
附上上一段的英文原文：
</p>
<p>
You should write a program which will find maximum length of The Golden Age which starts no earlier than the year l and ends no later than the year r. If all years in the interval [l, r] are unlucky then the answer is 0
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
第一行包含四个整数$x,y,l,r$ （$2 \leq x,y \leq 10^{18},1\leq l \leq r \leq 10^{18}$）。
</p>
<h3>
【输出格式】
</h3>
<p>
输出仅包含一行：在$[l,r]$中黄金年代的最大长度
</p>
<h3>
【样例】
</h3>
<pre>

<pre class="prettyprint">Input
2 3 1 10

Output
1</pre>
<pre class="prettyprint">Input
3 5 10 22

Output
8</pre>
<pre class="prettyprint">Input
2 3 3 5

Output
0</pre>
</pre>
<h3>
【来源】
</h3>
<p>
Educational Codeforces Round 22 B. The Golden Age <a href="http://codeforces.com/contest/813/problem/B" target="_blank">http://codeforces.com/contest/813/problem/B</a> 
</p>
<p>
数据：官方数据
</p>
<h3>
【提示】
</h3>
<p>
记得开unsigned long long 数据很鬼畜，注意溢出
</p>
