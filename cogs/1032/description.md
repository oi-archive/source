# 题目描述


<h1 style="text-align:center;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">2</span></b><b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">．最小交换排序</span></b> 
</h1>
<p align="center" style="text-align:center;text-indent:24.1pt;">
	<b></b> 
</p>
<p align="center" style="text-align:center;text-indent:15.8pt;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">  (minsort.pas/c/cpp) </span></b> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【问题描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">    小x最近切了一道很水的排序题，但是在AC之后，他想到了一个问题：</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">给定n个不相等的整数，将其按从小到大排序，你每次可以对任意一对数进行交换，问最少的交换次数是多少？</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输入】</span> 
</h3>
<p>
	<span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第一行：一个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">n</span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第二行：</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">个用空格隔开的正整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">ai</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，-2^31<ai<2^31< span=""><span></span> </ai<2^31<></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"> </span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输出】</span> 
</h3>
<p>
	<span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">一个整数，表示最小交换次数。</span><span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"> </span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输入输出样例</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">】</span> 
</h3>
<p>
	<span></span> 
</p>
<table border="1" cellspacing="0" cellpadding="0" style="border:none;">
	<tbody>
		<tr>
			<td width="283" valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">minsort.in</span> 
				</p>
			</td>
			<td width="283" valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">minsort.out</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="283" valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">8</span> 
				</p>
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">8 23 4 16 77 -5 53 100</span> 
				</p>
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"> </span> 
				</p>
			</td>
			<td width="283" valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">5</span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"> </span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【数据范围】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">   20%   n&lt;=100</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">   50%  
n&lt;=5000</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">   100% 
n&lt;=100000</span> 
</p>
