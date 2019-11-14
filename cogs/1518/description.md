# 题目描述


<h3>
【题目描述】
</h3>
<div class="ptx" lang="zh-CN">
Squares and rectangles fascinated the famous Dutch painter Piet Mondriaan. One night, after producing the drawings in his &#39;toilet series&#39; (where he had to use his toilet paper to draw on, for all of his paper was filled with squares and rectangles), he dreamt of filling a large rectangle with small rectangles of width 2 and height 1 in varying ways. <br/>
<center>
<img src="http://www.poj.org/images/2411_1.jpg"/> 
</center>
<br/>
Expert as he was in this material, he saw at a glance that he&#39;ll need a computer to calculate the number of ways to fill the large rectangle whose dimensions were integer values, as well. Help him, so that his dream won&#39;t turn into a nightmare!
</div>
<h3>
【输入格式】
</h3>
<div class="ptx" lang="zh-CN">
The input contains several test cases. Each test case is made up of two integer numbers: the height h and the width w of the large rectangle. Input is terminated by h=w=0. Otherwise, 1&lt;=h,w&lt;=11.
</div>
<h3>
【输出格式】
</h3>
<div class="ptx" lang="zh-CN">
<img src="http://www.poj.org/images/2411_2.jpg" align="right"/>For each test case, output the number of different ways the given rectangle can be filled with small rectangles of size 2 times 1. Assume the given large rectangle is oriented, i.e. count symmetrical tilings multiple times.
</div>
<h3>
【中文题意】
</h3>
<p>
给出 $h\times w$ ($1≤h, w≤11$)的方格棋盘，用 $1\times2$ 的长方形骨牌不重叠地覆盖这个棋盘，求覆盖满的方案数。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件包含多组数据。
</p>
<p>
每组数据有一行，两个正整数$h, w$。
</p>
<h3>
【输出格式】
</h3>
<p>
输入结束标志为$h=w=0$.
</p>
<p>
对每组数据，输出一行一个正整数，即方案总数。
</p>
<h3>
【样例输入】
</h3>
<pre class="sio">1 2
1 3
1 4
2 2
2 3
2 4
2 11
4 11
0 0
</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">1
0
1
2
3
5
144
51205
</pre>
<h3>
【来源】
</h3>
<p>
<a href="http://www.poj.org/problem?id=2411&amp;lang=zh-CN&amp;change=true" style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">POJ 2411</a>
</p>
