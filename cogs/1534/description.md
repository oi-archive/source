# 题目描述


<h3>
【中文题意】
</h3>
<p>
给出一个长度为n的序列a1~an，有m次询问(x,y,k)，每次询问a[x]~a[y]内的第k<strong>小</strong>数。
</p>
<p>
输入第一行为n,m，第二行为a1~an，接下来m行是m个(x,y,k)。
</p>
<p>
由于数据较大，请使用C风格的输入输出。
</p>
<p>
1&lt;=n&lt;=100000,1&lt;=m&lt;=5000
</p>
<h3>
【题目描述】
</h3>
<div class="ptx" lang="zh-CN">
You are working for Macrohard company in data structures department. After failing your previous task about key insertion you were asked to write a new data structure that would be able to return quickly k-th order statistics in the array segment. <br/>
That is, given an array a[1...n] of different integer numbers, your program must answer a series of questions Q(i, j, k) in the form: &#34;What would be the k-th number in a[i...j] segment, if this segment was sorted?&#34; <br/>
For example, consider the array a = (1, 5, 2, 6, 3, 7, 4). Let the question be Q(2, 5, 3). The segment a[2...5] is (5, 2, 6, 3). If we sort this segment, we get (2, 3, 5, 6), the third number is 5, and therefore the answer to the question is 5.
</div>
<h3>
【输入格式】
</h3>
<div class="ptx" lang="zh-CN">
The first line of the input file contains n --- the size of the array, and m --- the number of questions to answer (1 &lt;= n &lt;= 100 000, 1 &lt;= m &lt;= 5 000). <br/>
The second line contains n different integer numbers not exceeding 10<sup>9</sup> by their absolute values --- the array for which the answers should be given. <br/>
The following m lines contain question descriptions, each description consists of three numbers: i, j, and k (1 &lt;= i &lt;= j &lt;= n, 1 &lt;= k &lt;= j - i + 1) and represents the question Q(i, j, k).
</div>
<h3>
【输出格式】
</h3>
<div class="ptx" lang="zh-CN">
For each question output the answer to it --- the k-th number in sorted a[i...j] segment.
</div>
<h3>
【样例输入】
</h3>
<pre class="sio">7 3
1 5 2 6 3 7 4
2 5 3
4 4 1
1 7 3</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">5
6
3</pre>
<h3>
【提示】
</h3>
<div class="ptx" lang="zh-CN">
This problem has huge input,so please use c-style input(scanf,printf),or you may got time limit exceed.
</div>
<h3>
【来源】
</h3>
<div class="ptx" lang="zh-CN">
<a href="http://neerc.ifmo.ru/subregions/northern.html" target="_blank">Northeastern Europe 2004, Northern Subregion</a> 
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.poj.org/problem?id=2104&amp;lang=zh-CN&amp;change=true"> 北京大学 POJ 2104</a>
