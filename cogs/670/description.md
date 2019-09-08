# 题目描述


<p style="margin-left:0px;">
	<span style="font-family:sans-serif;line-height:28px;font-size:29px;">描述 </span><span><span style="font-size:30px;line-height:28px;">[USACO 1.5.2]</span></span> 
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	因为151既是一个质数又是一个回文数(从左到右和从右到左是看一样的)，所以 151 是回文质数。
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	写一个程序来找出范围[a,b](5 &lt;= a &lt; b &lt;= 100,000,000)( 一亿)间的所有回文质数;
</p>
<h2 style="font-weight:normal;margin-left:0px;font-size:29px;font-family:sans-serif;">
	<span><br/>
格式</span> 
</h2>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	<b>PROGRAM NAME</b>: pprime
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	<b>INPUT FORMAT</b>:
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	(file pprime.in)
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	第 1 行: 二个整数 a 和 b .
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	<b>OUTPUT FORMAT</b>:
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	(file pprime.out)
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	输出一个回文质数的列表，一行一个。
</p>
<h2 style="font-weight:normal;margin-left:0px;font-size:29px;font-family:sans-serif;">
	<span><br/>
SAMPLE INPUT</span> 
</h2>
<pre>5 500 
</pre>
<h2 style="font-weight:normal;margin-left:0px;font-size:29px;font-family:sans-serif;">
	<span><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre>5
7
11
101
131
151
181
191
313
353
373
383
</pre>
<h2 style="font-weight:normal;margin-left:0px;font-size:29px;font-family:sans-serif;">
	<span><br/>
提示 HINTS(小心使用 use them carefully!)</span> 
</h2>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	Hint 1: Generate the palindromes and see if they are prime. 提示 1: 找出所有的回文数再判断它们是不是质数（素数）.
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	Hint 2: Generate palindromes by combining digits properly. You might need more than one of the loops like below. 提示 2: 要产生正确的回文数，你可能需要几个像下面这样的循环。
</p>
<p style="margin-left:0px;font-family:sans-serif;font-size:19px;">
	产生长度为5的回文数:
</p>
<p>
	<br/>
</p>
<pre>for (d1 = 1; d1 &lt;= 9; d1+=2)  { 	// 只有奇数才会是素数       for (d2 = 0; d2 &lt;= 9; d2++)  {          for (d3 = 0; d3 &lt;= 9; d3++) {            palindrome = 10000*d1 + 1000*d2 +100*d3 + 10*d2 + d1;//(处理回文数...)         }     } }</pre>
<p>
	<br/>
</p>
<p>
	<br/>
</p>
