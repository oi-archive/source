# 题目描述


<h3>
【题目描述】
</h3>
<p>
给出n个整数，那么它们组成的集合有2^n-1个子集。请你计算其中有多少个子集，其中的所有元素之积是完全平方数。例如，集合{4,6,10,15}有三个这样的子集：{4},{6,10,15}和{4,6,10,15}。完全平方数是指平方根为整数的数。例如1,4,9,16,...
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含多组数据。
</p>
<p>
输入文件的第1行是一个整数T(1&lt;=T&lt;=30)，表示测试数据组数。
</p>
<p>
接下来是T组测试数据，每组占2行：
</p>
<p>
第1行是一个整数n(1&lt;=n&lt;=100)。
</p>
<p>
第2行是n个正整数，由空格分隔。这些正整数在区间[1,10^15]内。它们都不含超过500的素因子。
</p>
<h3>
【输出格式】
</h3>
<p>
对每组测试数据，输出一行：所有元素乘积为完全平方数的子集个数。
</p>
<h3>
【样例输入】
</h3>
<pre>4
3
2 3 5
3
6 10 15
4
4 6 10 15
3
2 2 2
</pre>
<h3>
【样例输出】
</h3>
<pre>0
1
3
3
</pre>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=489&amp;page=show_problem&amp;problem=2537" target="_blank">UVa 11542 Square</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2-12
</p>
<p>
Problemsetter: Abdullah al Mahmud
</p>
<p>
Special Thanks to: Manzurur Rahman Khan
</p>
