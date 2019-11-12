# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n 个数排成一排。一个数的M 数是指的在这个数的左边且比它小的数中最靠近它（即<br/>
 最靠右）的那个数。依次给出这n 个数，请求出所有这n 个数相对应的M 数。<br/>
</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">从文件allm.in 中读入数据。<br/>
 数据的第一行是一个正整数n，表示一共有多少个数。<br/>
 第二行有n 个用空格隔开的正整数，它们从左至右给出了数列中的n 个数。这些数保证<br/>
 小于2^31。<br/>
</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出一行用空格隔开的n 个数到文件allm.out。<br/>
 这些数对应输入数据中的数的M 数。如果输入中某个数没有M 数（即它左边的数都不<br/>
 比它小），请输出0。<br/>
</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>7
3 1 2 7 6 7 4
</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>0 0 1 2 2 6 2</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【提示】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">对于100%的数据，有n&lt;=1000000.</span> 
</p>
