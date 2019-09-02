# 题目描述


<p style="text-indent:21.2100pt;">
	给出一张地图，这张地图被分为n×m（n,m&lt;=100）个方块，任何一个方块不是平地就是高山。平地可以通过，高山则不能。现在你处在地图的（x1,y1）这块平地，问：你至少需要拐几个弯才能到达目的地（x2,y2）？你只能沿着水平和垂直方向的平地上行进，拐弯次数就等于行进方向的改变（从水平到垂直或从垂直到水平）的次数。
</p>
<p style="text-indent:21.2100pt;">
	例如：如图1，最少的拐弯次数为5。
</p>
<p style="text-indent:21.2100pt;">
	<img src="/upload/image/20121008/20121008093350_39927.png" alt=""/><br/>
       
</p>
<p>
	输入：共三行
</p>
<p style="text-indent:10.5000pt;">
	第一行：n   m
</p>
<p style="text-indent:10.5000pt;">
	第2至n+1行：整个地图地形描述（0：空地；1：高山），
</p>
<p style="text-indent:52.5000pt;">
	如（图1）第2行地形描述为：1 0 0 0 0 1 0
</p>
<p style="text-indent:52.5000pt;">
	          第3行地形描述为：0 0 1 0 1 0 0
</p>
<p style="text-indent:63.0000pt;">
	          ……
</p>
<p>
	          最后放在同一行。
</p>
<p style="text-indent:42.0000pt;">
	          
</p>
<p style="text-indent:10.5000pt;">
	第n+2行：x1  y1  x2  y2  （分别为起点、终点坐标）
</p>
<p style="text-indent:10.5000pt;">
	<br/>
</p>
<p>
	输出：s （即最少的拐弯次数）
</p>
<p>
	<br/>
</p>
<p>
	输入输出样例（见图1）：
</p>
<p>
	<br/>
</p>
<table style="padding:0pt 5.4pt;">
	<tbody>
		<tr>
			<td width="175" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">turn.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="132" valign="top" style="border:0.5000pt solid #000000;">
				<span style="font-size:14.166666030883789px;line-height:17.5px;">turn.out</span>
			</td>
		</tr>
		<tr>
			<td width="175" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 7</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 0 0 0 0 1 0 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 1 0 1 0 0 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 0 0 1 0 1 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 1 1 0 0 0 0 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 0 0 1 1 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 3 1 7</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="132" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<br/>
</p>
