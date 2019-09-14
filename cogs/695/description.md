# 题目描述


<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:28px;font-family:sans-serif;">
	<span>描述 USACO 2.2.4  Source: IOI&#39;98</span> 
</h2>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	在IOI98的节日宴会上，我们有N(10&lt;=N&lt;=100)盏彩色灯，他们分别从1到N被标上号码。 这些灯都连接到四个按钮：
</p>
<pre>按钮1：当按下此按钮，将改变所有的灯：本来亮着的灯就熄灭，本来是关着的灯被点亮。 
按钮2：当按下此按钮，将改变所有奇数号的灯。
按钮3：当按下此按钮，将改变所有偶数号的灯。
按钮4：当按下此按钮，将改变所有序号是3*K+1(K&gt;=0)的灯。例如：1,4,7...
</pre>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	一个计数器C记录按钮被按下的次数。当宴会开始，所有的灯都亮着，此时计数器C为0。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	你将得到计数器C(0&lt;=C&lt;=10000)上的数值和经过若干操作后某些灯的状态。写一个程序去找出所有灯最后可能的与所给出信息相符的状态，并且没有重复。
</p>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:28px;font-family:sans-serif;">
	<span><br/>
格式</span> 
</h2>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	<b>PROGRAM NAME</b>: lamps
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	<b>INPUT FORMAT</b>:
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	(file lamps.in)
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	不会有灯会在输入中出现两次。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	第一行: N。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	第二行: C最后显示的数值。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	第三行: 最后亮着的灯,用一个空格分开，以-1为结束。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	第四行: 最后关着的灯,用一个空格分开，以-1为结束。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	<b>OUTPUT FORMAT</b>:
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	(file lamps.out)
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	每一行是所有灯可能的最后状态(没有重复)。每一行有N个字符，第1个字符表示1号灯，最后一个字符表示N号灯。0表示关闭，1表示亮着。这些行必须从小到大排列（看作是二进制数）。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	如果没有可能的状态，则输出一行&#39;IMPOSSIBLE&#39;。
</p>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:28px;font-family:sans-serif;">
	<span><br/>
SAMPLE INPUT</span> 
</h2>
<pre>10
1
-1
7 -1
</pre>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	在这个样例中，有10盏灯，只有1个按钮被按下。最后7号灯是关着的。
</p>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:28px;font-family:sans-serif;">
	<span><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre>0000000000
0101010101
0110110110
</pre>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	在这个样例中，有三种可能的状态：
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	所有灯都关着
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	1,4,7,10号灯关着，2,3,5,6,8,9亮着。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
	1,3,5,7,9号灯关着，2, 4, 6, 8, 10亮着。
</p>
