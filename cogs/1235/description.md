# 题目描述


<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">在一个被分割为<span>N*M</span><span>个正方形房间的矩形魔鬼之城中，一个探险者必须遵循下列规则才能跳跃行动。他必须从</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1, 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">进入，从</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">N, M</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">走出；在每一房间的墙壁上都写了一个魔法数字，是<span>1</span><span>～</span><span>13</span><span>之内的自然数；探险者可以想像出</span><span>8</span><span>个方向中的任何一个</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">水平或垂直或对角线方向</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，随后他就可以作一次空间跳跃穿过这一方向上的连续的<span>X</span><span>个房间，其中</span><span>X</span><span>是他原来所在房间的魔法数字。但如果在这一方向上的房间数小于</span><span>X</span><span>，则他不作任何跳跃，而必须想像另一个方向。同时，探险者不能作连续两次相同方向的跳跃。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<table align="center" style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td width="22" valign="center" style="border:31.8750pt none #FFFFFF;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="26" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">5</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="22" valign="center" style="border:31.8750pt none #FFFFFF;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">6</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">7</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="26" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">11</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="22" valign="center" style="border:31.8750pt none #FFFFFF;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="26" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="22" valign="center" style="border:31.8750pt none #FFFFFF;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="26" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="22" valign="center" style="border:31.8750pt none #FFFFFF;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="22" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="26" valign="center" style="border:0.5000pt solid #000000;background:#F3F3F3;">
				<p style="text-align:center;">
					<span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">例如在上图的<span>5*4</span><span>的魔鬼之城中，如果探险者现在所在的位置是</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3, 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，那么通过依次空间跳跃他可以到达下列房间中的一个：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1, 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3, 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1, 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5, 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，或</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5, 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。另外，如果他要用两次跳跃从</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5, 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">到达</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3, 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，则他不能首先跳到</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4, 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">因为这样他第二次跳跃的方向将和第一次相同，而这是不允许的</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。所以他必须先跳跃到</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2, 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">请你写一个程序，对给定的地图，算出探险者至少需要跳跃多少步才能离开魔鬼之城。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一行给出<span>N</span><span>，</span><span>M</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">都不超过<span>100</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">；</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">下来有<span>M</span><span>行，每行为</span><span>N</span><span>个自然数，表示对应房间中的魔法数字。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">出最小步数，如果探险者无法离开魔鬼之城，请输出“<span>NEVER</span><span>”。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">pils.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 3 6 7 11</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 2 1 1 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 2 2 1 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 1 2 2 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">pils.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<br/>
</p>
