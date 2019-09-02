# 题目描述


<div>
	<p style="text-indent:24.1pt;">
		<span style="color:#FF9900;font-family:&#34;Microsoft YaHei&#34;;font-size:18px;background-color:#000000;"><span style="color:#FF9900;font-family:&#34;Microsoft YaHei&#34;;font-size:18px;background-color:#000000;"><b>Source: GZOI2011  Rail</b></span></span> 
	</p>
	<p style="text-indent:21pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">提交文件：</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;"><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">highrail.cpp/c/pas</span></span> 
	</p>
	<p style="text-indent:21pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">输入文件：</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;"><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">highrail.in</span></span> 
	</p>
	<p style="text-indent:21pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">输出文件：</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;"><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">highrail.out</span></span> 
	</p>
	<p style="text-indent:21.1pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;font-weight:bold;">题目描述</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">：</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;font-weight:bold;"></span> 
	</p>
	<p style="text-indent:21pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">你所在的省刚获得国家拨款兴建高铁，高铁的起止城市是国家选定的，中途可能经过若干城市。根据国家拨款的政策，国家将负担费用最大的两个区间，其余的必须由省负担。假如高铁线路中途只经过一个城市，国家只负担费用较大的区间。假如是直达的，国家将不负担任何费用。</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
	</p>
	<p style="text-indent:21pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">你被省里选定作为这个项目的总工程师，你必须规划出一条高铁线路，使得省负担的费用最少。当然，路线上每个城市最多只经过一次。</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
	</p>
	<p style="text-indent:21.1pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;font-weight:bold;">输入格式</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">（</span> <span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">highrail</span> <span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">.in</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">）：</span></span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
	</p>
	<p style="text-indent:21pt;">
		<span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">第一行是一个正整数</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">n</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">，</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">n&lt;=50</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">，代表城市之间的高铁建设费用估算（注意并非每对城市之间的建设费用都进行了估算）。接下来</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">n</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">行是用空格分隔的三个整数</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">s,e,c</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">。</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">s</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">和</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">e</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">代表城市的编码，高铁的起点和终点城市分别是编码为</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">0</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">和</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">1</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">，其余的城市依次编码。</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">c&lt;=1000</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">，是在</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">s</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">和</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">e</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">之间建设费用估算，从</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">s</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">到</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">e</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">与从</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">e</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">到</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">s</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">的建设费用是相同的。</span></span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
	</p>
	<p style="text-indent:21.1pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;font-weight:bold;">输出格式</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">（</span> <span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">highrail</span> <span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">.out</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">）：</span></span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
	</p>
	<p style="text-indent:21pt;">
		<span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">输出只有一行，格式为</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">c1 c2 </span></span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">…</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;"> cm cost</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">，各数字用一个空格分隔，代表高铁线路规划和省负担的费用。</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">ci</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">代表城市编码（注意</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">c1=0</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">，</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">cm=1</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">），</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">cost</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">是费用。我们保证输入肯定有解，如果有多个解，输出当中经过城市最少的解，如果仍有多个解，则输出当中按字典序排列最小的解。</span></span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
	</p>
	<p style="text-indent:21.1pt;">
		<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;font-weight:bold;">样例</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;font-weight:bold;"></span> 
	</p>
<br/>
	<table style="padding:0pt 5.4pt;border-collapse:collapse;">
		<tbody>
			<tr>
				<td width="284" valign="top">
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">highrail</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">.in</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
					</p>
				</td>
				<td width="284" valign="top">
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">highrail</span><span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">.out</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="284" valign="top">
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">7</span><span style="font-family:&#34;MS Mincho&#34;;font-size:10.5pt;"></span> 
					</p>
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">0 2 10</span><span style="font-family:&#34;MS Mincho&#34;;font-size:10.5pt;"></span> 
					</p>
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">0 3 6</span><span style="font-family:&#34;MS Mincho&#34;;font-size:10.5pt;"></span> 
					</p>
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">2 4 5</span><span style="font-family:&#34;MS Mincho&#34;;font-size:10.5pt;"></span> 
					</p>
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">3 4 3</span><span style="font-family:&#34;MS Mincho&#34;;font-size:10.5pt;"></span> 
					</p>
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">3 5 4</span><span style="font-family:&#34;MS Mincho&#34;;font-size:10.5pt;"></span> 
					</p>
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">4 1 7</span><span style="font-family:&#34;MS Mincho&#34;;font-size:10.5pt;"></span> 
					</p>
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">5 1 8</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
					</p>
				</td>
				<td width="284" valign="top">
					<p style="text-indent:21pt;">
						<span style="font-family:&#34;Microsoft YaHei&#34;;font-size:18px;">0 3 4 1 3</span><span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
	<p style="text-indent:21pt;">
		<span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"></span> 
	</p>
</div>
