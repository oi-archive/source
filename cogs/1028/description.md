# 题目描述


<p align="center" style="text-align:center;background:white;">
	<b><span style="font-family:Microsoft YaHei;">引爆炸弹</span><span></span></b> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">问题描述：</span><span></span></b> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:Microsoft YaHei;">有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">个炸弹，有些炸弹牵了一根单向引线（也就是说引线只有在这一端能被炸弹点燃），只要引爆了这个炸弹，用引线连接的下一个炸弹也会爆炸。每个炸弹还有个得分，当这个炸弹被引爆后就能得到相应得分。</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:Microsoft YaHei;">现在要你引爆</span><span style="font-family:&#39;Microsoft YaHei&#39;;">k</span><span style="font-family:Microsoft YaHei;">个炸弹，使得分最大。</span><span></span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">输入说明：</span><span></span></b> 
</p>
<p style="text-indent:24.0pt;">
	<span style="font-family:Microsoft YaHei;">第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:Microsoft YaHei;">行两个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">、</span><span style="font-family:&#39;Microsoft YaHei&#39;;">k</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p style="text-indent:24.0pt;">
	<span style="font-family:Microsoft YaHei;">接下来</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">行每行两个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">a[i]</span><span style="font-family:Microsoft YaHei;">、</span><span style="font-family:&#39;Microsoft YaHei&#39;;">b[i]</span><span style="font-family:Microsoft YaHei;">。</span><span style="font-family:&#39;Microsoft YaHei&#39;;">a[i]</span><span style="font-family:Microsoft YaHei;">表示这个炸弹用引线连接的下一个炸弹，如果</span><span style="font-family:&#39;Microsoft YaHei&#39;;">a[i]</span><span style="font-family:Microsoft YaHei;">为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-family:Microsoft YaHei;">，则表示这个炸弹没连接引线。</span><span style="font-family:&#39;Microsoft YaHei&#39;;">b[i]</span><span style="font-family:Microsoft YaHei;">表示这个炸弹的得分。</span><span></span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">输出说明：</span><span></span></b> 
</p>
<p style="text-indent:24.0pt;">
	<span style="font-family:Microsoft YaHei;">仅一个数，表示最大得分。</span><span></span> 
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
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">bombb</span><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">.in</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="568" valign="top" style="border:solid black 1.0pt;">
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">8 2</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">0 1</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">1 1</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">2 100</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">2 100</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">0 1</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">5 1</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">6 2</span> 
				</p>
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">6 2</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="568" valign="top" style="border:solid black 1.0pt;">
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">bombb</span><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">.out</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="568" valign="top" style="border:solid black 1.0pt;">
				<p>
					<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">202</span> 
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
	<b><span style="font-family:Microsoft YaHei;">    </span></b><span style="font-family:Microsoft YaHei;">1≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">b[i]</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1000000</span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">    </span></b><span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">30%</span><span style="font-family:Microsoft YaHei;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1000  k</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">30</span> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">60%</span><span style="font-family:Microsoft YaHei;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">50000 k</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100</span> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100%</span><span style="font-family:Microsoft YaHei;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">200000   k</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">500</span> 
</p>
