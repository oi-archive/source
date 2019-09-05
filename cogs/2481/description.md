# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span lang="en-us"></span> 
</p>
<p>
给定一个n*n的矩阵A和一个正整数k，求S=A+A^2+A^3+...+A^k。
</p>
<h3>
【输入格式】
</h3>
<p>
<span lang="en-us"></span> 
</p>
<p>
第一行三个正整数n,k,m。
</p>
<p>
以下n行，每行n个小于m的非负整数，表示矩阵A。
</p>
<h3>
【输出格式】
</h3>
<p>
n行，每行n个数，表示矩阵S中的每个元素mod m的值。
</p>
<h3>
【样例输入】
</h3>
<pre class="sio">2 2 4
0 1
1 1</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">1 2
2 3</pre>
<h3>
【数据范围与约定】
</h3>
<p>
对于30%的数据，k&lt;=10^5。
</p>
<p>
对于60%的数据，m&lt;=10^8。
</p>
<p>
对于100%的数据，n&lt;=30，k&lt;=10^10，m&lt;=10^18。
</p>
<h3>
【来源】
</h3>
<a href="http://www.poj.org/problem?id=3233&amp;lang=zh-CN&amp;change=true"> 北京大学 POJ 3233</a>
