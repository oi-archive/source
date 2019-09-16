# 题目描述


<h1 style="text-align:center;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">1</span></b><b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">．足球积分(简化版)</span></b> 
</h1>
<p align="center" style="text-align:center;text-indent:24.1pt;">
	<b></b> 
</p>
<h2 style="text-align:center;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">  (footballc.pas/c/cpp)</span></b> 
</h2>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【问题描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    很多球类比赛采用的都是联赛制，足球也是。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    在各大足球联赛中，比赛场次都很多，一般采用积分制来排名，于是每场比赛的结果都很重要；</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">足球联赛的积分制是这样的：如果球队获胜一场（球队比分不会相等，只会大于），获得3分，平局获得1分，输球不得分。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    现在的问题是：如果你可以操纵比赛，给你三个数N,x和y，表示在N场比赛中，一个球队进了x个球，丢了y个球，问最多能得多少分。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入】</span> 
</h3>
<p>
	<span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行一个整数T，表示测试数据组数。<br/>
</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来T行，每行三个整数：</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">x</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">y</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">和 </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">  </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2*10^9&gt;x,y&gt;=0,  2*10^9&gt;N&gt;=1;</span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出】</span> 
</h3>
<p>
	<span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">T行，每行两个整数，表示：最大得分。</span><span></span> 
</p>
<p>
	<span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入输出样例】</span> 
</h3>
<p>
	<span></span> 
</p>
<table border="1" cellspacing="0" cellpadding="0">
	<tbody>
		<tr>
			<td width="283" valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">football.in</span> 
				</p>
			</td>
			<td width="283" valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">football</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">.out</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="283" valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2<br/>
1 1 1</span> 
				</p>
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 1 2</span> 
				</p>
			</td>
			<td width="283" valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
				</p>
				<p align="left" style="text-align:left;">
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
				</p>
				<p>
					<span style="font-family:;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据范围】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">   </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于每个输入文件：</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">30%</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据组数不超过</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">50</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">组，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">100%</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据不超过</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">30000</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">组。</span><span></span> 
</p>
