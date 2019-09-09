# 题目描述


<table style="padding:0pt 5.4pt;border-collapse:collapse;">
	<tbody>
		<tr>
			<td width="111" valign="top" style="background:#C0504D;border:1pt solid #CF7B79;" colspan="2">
				<p>
					<span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:16pt;font-weight:bold;"="">Problem 1</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="552" valign="top" style="background:#C0504D;border:1pt solid #CF7B79;">
				<p>
					<span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16px;font-weight:bold;">射命丸文</span><span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:16pt;font-weight:bold;"="">(</span><span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16px;font-weight:bold;">aya</span><span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:16pt;font-weight:bold;"="">.cpp/c/pas)</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">题目描述</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">在幻想乡，</span><a href="http://wiki.touhou8.com/index.php?doc-view-213.html" target="_blank"><span style="font-family:Microsoft YaHei;font-size:16px;">射命丸文（しゃめいまる　あや）</span><br/>
</a><span style="font-family:Microsoft YaHei;font-size:16px;">是以偷拍闻名的鸦天狗。当然，文文的照相机可不止能够照相，还能够消除取景框里面所有的弹幕。假设现在文文面前有一块</span><span style="font-family:Microsoft YaHei;font-size:16px;">N</span><span style="font-family:Microsoft YaHei;font-size:16px;">行</span><span style="font-family:Microsoft YaHei;font-size:16px;">M</span><span style="font-family:Microsoft YaHei;font-size:16px;">列的弹幕群，每一个单位面积内有分值有</span><span style="font-family:Microsoft YaHei;font-size:16px;">num[i][j]</span><span style="font-family:Microsoft YaHei;font-size:16px;">的弹幕。相机的取景框可以将一块</span><span style="font-family:Microsoft YaHei;font-size:16px;">R</span><span style="font-family:Microsoft YaHei;font-size:16px;">行</span><span style="font-family:Microsoft YaHei;font-size:16px;">C</span><span style="font-family:Microsoft YaHei;font-size:16px;">列的弹幕消除，并且得到这一块区域内所有弹幕的分值</span><span style="font-family:Microsoft YaHei;font-size:16px;">(</span><span style="font-family:Microsoft YaHei;font-size:16px;">累加</span><span style="font-family:Microsoft YaHei;font-size:16px;">)</span><span style="font-family:Microsoft YaHei;font-size:16px;">。现在文文想要取得尽可能多的分值，请你计算出她最多能够得到的分值。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #CF7B79;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">输入格式</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #CF7B79;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：</span><span style="font-family:Microsoft YaHei;font-size:16px;">4</span><span style="font-family:Microsoft YaHei;font-size:16px;">个正整数</span><span style="font-family:Microsoft YaHei;font-size:16px;">N,M,R,C</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">2..N+1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：每行</span><span style="font-family:Microsoft YaHei;font-size:16px;">M</span><span style="font-family:Microsoft YaHei;font-size:16px;">个正整数，第</span><span style="font-family:Microsoft YaHei;font-size:16px;">i+1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行第</span><span style="font-family:Microsoft YaHei;font-size:16px;">j</span><span style="font-family:Microsoft YaHei;font-size:16px;">个数表示</span><span style="font-family:Microsoft YaHei;font-size:16px;">num[i][j]</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">输出格式</span><span style="font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">个整数，表示文文能够取得的最大得分</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #CF7B79;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">输入样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #CF7B79;" colspan="2">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">3 5 2 </span><span style="font-family:Microsoft YaHei;font-size:16px;">3</span><span style="font-family:;" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">5 2 7 1 1</span><span style="font-family:;" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">5 9 5 1 5</span><span style="font-family:;" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">3 5 1 5 3</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">输出样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;" colspan="2">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">33</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #CF7B79;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">数据范围</span><span style="font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #CF7B79;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">对于</span><span style="font-family:Microsoft YaHei;font-size:16px;">60%</span><span style="font-family:Microsoft YaHei;font-size:16px;">的数据：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= N,M &lt;= 200</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">对于</span><span style="font-family:Microsoft YaHei;font-size:16px;">100%</span><span style="font-family:Microsoft YaHei;font-size:16px;">的数据：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= N,M &lt;= 1,000</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= R &lt;= N, 1 &lt;= C &lt;= M</span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= num[i][j] &lt;= 1000</span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">保证结果不超过</span><span style="font-family:Microsoft YaHei;font-size:16px;">2,000,000,000</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<img alt="" src="/upload/image/20120808/20120808150227_39069.jpg"/><br/>
<span><span style="line-height:normal;"><br/>
</span></span> 
</p>
