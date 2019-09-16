# 题目描述


<p style="text-indent:15.7500pt;text-align:center;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">  </span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Courier New&#39;;">(</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">gitara</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.pas/c/cpp) </span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">小<span>x</span><span>有一个神密的朋友： 一个外星人，这个外星人有无数个触角，还有一把很神奇的吉他。小</span><span>x</span><span>最近一个爱好就是听外星人弹吉他。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">这个吉他和非常巨大，有<span>6</span><span>根弦，每根弦有</span><span>P</span><span>个</span>品丝，编号为<span>1..P,</span><span>每根弦的每个品丝可以发出不同的乐音，且乐音的音调随着品丝的编号依次增加。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">因为外星人有无数个触角，他可以</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">触动</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">很多个不同的品丝，来发出不同的乐音。这个吉他的神奇之处在于，如果外星人</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">触动</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">某根弦上多个品丝，它只会发出音调最高的乐音（品丝编号最高发出的乐音）。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">现在，小<span>x</span><span>想让外星人朋友弹一首包含</span><span>N</span><span>个乐音的曲子，而外星人朋友则想让小</span><span>x</span><span>首先计算出他最少移动多少次触角能够完成这首曲子的弹奏。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行包含两个整数：<span>N</span><span>和</span><span>P</span><span>，表示曲子有</span><span>N</span><span>个乐音，吉他的每根弦上有</span><span>P</span><span>个品丝。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来<span>N</span><span>行，每行两个整数</span><span>xi</span><span>和</span><span>yi</span><span>，表示第</span><span>i</span><span>个乐音需要</span>触动第<span>xi</span><span>跟弦上的第</span><span>yi</span><span>个品丝。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个整数，表示最小的移动触角的次数。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>1</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">gitara</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">gitara</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p style="margin-left:13.0000pt;text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">5 15</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="margin-left:13.0000pt;text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 8</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="margin-left:13.0000pt;text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 10</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="margin-left:13.0000pt;text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 12</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="margin-left:13.0000pt;text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 10</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="margin-left:13.0000pt;text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 5</span><span style="font-size:11.0000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">7</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例解释】 第一个乐音需要移动<span>1</span><span>次触角，第二个也是</span><span>1</span><span>次，第三个也是</span><span>1</span><span>次，第四次需要把编号为</span><span>12</span><span>的品丝松开，也是</span><span>1</span><span>次，第</span><span>5</span><span>次需要把编号为</span><span>8,10</span><span>的品丝松开，并触动编号为</span><span>5</span><span>的品丝，需要</span><span>3</span><span>次。所以一共是</span><span>7</span><span>次。 </span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>2</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">gitara</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">gitara</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">7 15</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">1 5</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 3</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 5</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 7</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 4</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">1 5</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">1 3</span><span style="font-size:11.0000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">9</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例解释】依次移动触角的次数是：</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">1, 1,</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">1, </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">1</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">, 3,</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">0, 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【数据范围】 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   50% <span>数据保证 </span><span>0&lt;=N,P&lt;=5000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   100% <span>数据保证  </span><span>0&lt;=N&lt;=500000   0&lt;=P&lt;=300000.</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
