# 题目描述


<h3>
【题目描述】
</h3>
<p>
考虑如下所示的递推关系：
</p>
<p>
$f(n)=a_1f(n-1)+a_2f(n-2)+...+a_df(n-d)(n&gt;d)$
</p>
<p>
$a_1,a_2,...,a_d\in Z$
</p>
<p>
一个著名的例子是$Fibonacci$数列：$f(1)=1,f(2)=1,f(n)=f(n-1)+f(n-2)$，在这里$d=2,a_1=1,a_2=1$.
</p>
<p>
每一个这样的递推关系都由$d$（即递推的阶数），$a_1,a_2,...,a_d$的值，$f(1),f(2),...,f(d)$的值唯一确定。给你这些值，和两个正整数$n,m$。你的任务是计算$f(n)\mod m$的值。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件包含多组数据。
</p>
<p>
每组数据有3行：
</p>
<p>
第1行是3个正整数$d,n,m$。
</p>
<p>
第2行是d个非负整数$a_1,a_2,...,a_d$。
</p>
<p>
第3行是d个整数$f(1),f(2),...,f(d)$。
</p>
<p>
两组数据之间由一个空行分隔。
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据，输出一行1个非负整数：$f(n)\mod m$的值。
</p>
<h3>
【样例输入】
</h3>
<pre>1 1 100
2
1

2 10 100
1 1
1 1

3 2147483647 12345
12345678 0 12345
1 2 3

0 0 0
</pre>
<h3>
【样例输出】
</h3>
<pre>1
55
423
</pre>
<h3>
【提示】
</h3>
<p>
数据组数&lt;=$150$
</p>
<p>
对于100%的数据：
</p>
<p>
$1&lt;=d&lt;=15$
</p>
<p>
$1&lt;=n&lt;=2^{31}-1$
</p>
<p>
$1&lt;=m&lt;=46340$
</p>
<p>
所有的输入数据均在$32$位带符号整数范围内。
</p>
<p>
输入结束标志为$d=n=m=0$.
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=489&amp;page=show_problem&amp;problem=1811" target="_blank">UVa 10870 Recurrences</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2-12
</p>
<p>
Problem setter: Max Furlong
</p>
<p>
Special Thanks: Derek Kisman, EPS.
</p>
