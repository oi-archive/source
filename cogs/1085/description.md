# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;background-color:#666666;color:#DFC5A4;">福州NOIP2010暑假Day1</span> 
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	老师在开学第一天就把所有作业都布置了，每个作业如果在规定的时间内交上来的话才有学分。每个作业的截止日期和学分可能是不同的。例如如果一个作业学分为10，要求在6天内交，那么要想拿到这10学分，就必须在第6天结束前交。
</p>
<p style="text-indent:21.0000pt;">
	每个作业的完成时间都是只有一天。例如，假设有7次作业的学分和完成时间如下：
</p>
<p style="text-indent:21.0000pt;">
	作业号           1  2  3  4  5  6  7 
</p>
<p style="text-indent:21.0000pt;">
	期限             1  1  3  3  2  2  6 
</p>
<p style="text-indent:21.0000pt;">
	学分             6  7  2  1  4  5  1 
</p>
<p style="text-indent:21.0000pt;">
	最多可以获得15学分，其中一个完成作业的次序为2，6，3，1，7，5，4，注意可能还有其他方法。
</p>
<p style="text-indent:21.0000pt;">
	你的任务就是找到一个完成作业的顺序获得最大学分。
</p>
<p>
	<br/>
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	第一行一个整数N，表示作业的数量。接下来N行，每行包括两个整数，第一个整数表示作业的完成期限，第二个数表示该作业的学分。
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	输出一个整数表示可以获得的最大学分。保证答案不超过longint范围。
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>7
1 6
1 7
3 2
3 1
2 4
2 5
6 1
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>15</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:20.2500pt;">
	对于所有数据，N&lt;=1000000，作业的完成期限均小于700000。
</p>
<p style="text-indent:20.2500pt;">
	对于部分数据，N&lt;=1000；
</p>
<p style="text-indent:20.2500pt;">
	对于部分数据，N&lt;=10000；
</p>
<p style="text-indent:20.2500pt;">
	对于部分数据，N&lt;=100000；
</p>
<p style="text-indent:20.2500pt;">
	对于部分数据，作业的完成期限小于100；
</p>
<p style="text-indent:20.2500pt;">
	对于部分数据，作业的完成期限小于1000；
</p>
<p>
	<br/>
</p>
