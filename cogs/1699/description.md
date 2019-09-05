# 题目描述


<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【题目描述】
</h3>
<p style="font-family:serif;font-size:16px;">
<br/>
</p>
<p>
对于一组有限个数的数据来说，它们的中位数是这样的一种数：这群数据里的一半的数据比它大，而另外一半数据比它小。 计算有限个数的数据的中位数的方法是：把所有的同类数据按照大小的顺序排列。如果数据的个数是奇数，则中间那个数据就是这群数据的中位数；如果数据的个数是偶数，则中间那2个数据的算术平均值就是这群数据的中位数。
</p>
<p>
<br/>
</p>
<p>
给定一个长度为N的数列A，求数列A的中位数。
</p>
<p>
<br/>
</p>
<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【输入格式】
</h3>
<p style="font-family:serif;font-size:16px;">
<br/>
</p>
<p>
第一行：一个正整数N，代表数列A的长度。
</p>
<p>
第二行：N个用空格隔开的整数，代表数列A的每个元素。
</p>
<p>
<br/>
</p>
<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【输出格式】
</h3>
<p style="font-family:serif;font-size:16px;">
一行：数列A的中位数，保留一位小数。
</p>
<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【样例输入1】
</h3>
<pre><p>
3
</p>

<p>
-1 0 233
</p>
</pre>
<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【样例输出1】
</h3>
<pre>0.0</pre>
<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【样例输入2】
</h3>
<pre><p>
4
</p>

<p>
-1 0 233 233<span style="line-height:1.5;"></span> 
</p>
</pre>
<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【样例输出2】
</h3>
<pre>116.5</pre>
<h3 style="font-family:sans-serif;font-size:20px;background-color:#F0F8FF;">
【提示】
</h3>
<p style="font-family:serif;font-size:16px;">
<br/>
</p>
<p>
对于N：0&lt;N&lt;=500000
</p>
<p>
对于数列A的任一元素A[k]：-20000000&lt;=A[k]&lt;=20000000
</p>
<p>
输入保证行末无多余空格符，文末无多余换行符。
</p>
<p>
<br/>
</p>
