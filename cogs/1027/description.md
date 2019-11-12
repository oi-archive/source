# 题目描述


<p align="center" style="text-align:center;background:white;">
	<b><span style="font-family:Microsoft YaHei;">取石子</span></b><b></b> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">问题描述</span><span style="font-family:&#39;Microsoft YaHei&#39;;">:</span></b> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">个石子围成一圈，每个石子都有一个权值</span><span style="font-family:&#39;Microsoft YaHei&#39;;">a[i]</span><span style="font-family:Microsoft YaHei;">，你需要取一些石子，每个石子的得分是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">a[i]*d</span><span style="font-family:Microsoft YaHei;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">d</span><span style="font-family:Microsoft YaHei;">表示这个石子到两边被取了的石子的距离和。</span><span></span> 
</p>
<p style="text-indent:20.25pt;">
	<br/>
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">现在你可以取若干石子，使得分最大。</span><span></span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> <img src="/upload/image/20120916/20120916192608_49723.png" alt=""/></span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">输入说明：</span><span></span></b> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:Microsoft YaHei;">行一个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">接下来</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">行，每行一个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">a[i]</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">输出说明：</span><span></span></b> 
</p>
<p style="text-indent:24.0pt;">
	<span style="font-family:Microsoft YaHei;">仅一个整数，表示最大得分。</span><span></span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">样例输入输出：</span><span></span></b> 
</p>
<table border="1" cellspacing="0" cellpadding="0" style="border:none;">
	<tbody>
		<tr>
			<td width="568" valign="top" style="border:solid black 1.0pt;">
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">stone</span><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">.in</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="568" valign="top" style="border:solid black 1.0pt;">
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">5</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">1</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">2</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">3</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">4</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">20</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="568" valign="top" style="border:solid black 1.0pt;">
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">stone</span><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">.out</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="568" valign="top" style="border:solid black 1.0pt;">
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">80</span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">数据范围：</span><span></span></b> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">    </span></b><span style="font-family:Microsoft YaHei;">1≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">a[i]</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100000</span> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">30%</span><span style="font-family:Microsoft YaHei;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">60</span> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">60%</span><span style="font-family:Microsoft YaHei;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">300</span> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100%</span><span style="font-family:Microsoft YaHei;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100000</span> 
</p>
