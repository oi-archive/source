# 题目描述


<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">现有<span>r</span><span>个互不相同的盒子和</span><span>n</span><span>个互不相同的球，要将这</span><span>n</span><span>个球放入</span><span>r</span><span>个盒子中，且不允许有空盒子。问有多少种方法？</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">例如：有<span>2</span><span>个不同的盒子（分别编为</span><span>1</span><span>号和</span><span>2</span><span>号）和</span><span>3</span><span>个不同的球（分别编为</span><span>1</span><span>、</span><span>2</span><span>、</span><span>3</span><span>号），则有</span><span>6</span><span>种不同的方法：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>号盒子</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>、</span><span>2</span><span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>、</span><span>3</span><span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2<span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2<span>、</span><span>3</span><span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3<span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2<span>号盒子</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2<span>、</span><span>3</span><span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3<span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2<span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>、</span><span>3</span><span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
			<td width="90" valign="center" style="border:0.5000pt solid #000000;">
				<p style="text-align:center;">
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>、</span><span>2</span><span>号球</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">两个整数，<span>n</span><span>和</span><span>r</span><span>，中间用空格分隔。（</span><span>0</span><span>≤</span><span>n, r</span><span>≤</span><span>10</span><span>）</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">仅一行，一个整数（保证在长整型范围内）。表示<span>n</span><span>个球放入</span><span>r</span><span>个盒子的方法。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">box.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">box.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">6</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<br/>
</p>
