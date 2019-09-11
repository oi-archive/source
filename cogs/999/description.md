# 题目描述


<table style="padding:0pt 5.4pt;border-collapse:collapse;">
	<tbody>
		<tr>
			<td width="111" valign="top" style="background:#4F81BD;border:1pt solid #7BA0CD;" colspan="2">
				<p>
					<span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:16pt;font-weight:bold;"="">Problem </span><span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16px;font-weight:bold;">3</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="552" valign="top" style="background:#4F81BD;border:1pt solid #7BA0CD;">
				<p>
					<span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16px;font-weight:bold;">雾雨魔理沙</span><span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:16pt;font-weight:bold;"="">(</span><span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16px;font-weight:bold;">marisa</span><span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:16pt;font-weight:bold;"="">.cpp/c/pas)</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#D3DFEE;border:1pt solid #7BA0CD;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">题目描述</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#D3DFEE;border:1pt solid #7BA0CD;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">在幻想乡，<a href="http://wiki.touhou8.com/index.php?doc-view-56.html" target="_blank">雾雨魔理沙（きりさめ まりさ）<span></span><strong><br/>
</strong></a>是住在魔法之森普通的黑魔法少女。话说最近魔理沙从香霖堂拿到了升级过后的的迷你八卦炉，她迫不及待地希望试试八卦炉的威力。在一个二维平面上有许多毛玉</span><span style="font-family:Microsoft YaHei;font-size:16px;">(</span><span style="font-family:Microsoft YaHei;font-size:16px;">一种飞行生物，可以视为点</span><span style="font-family:Microsoft YaHei;font-size:16px;">)</span><span style="font-family:Microsoft YaHei;font-size:16px;">，每个毛玉具有两个属性，分值</span><span style="font-family:Microsoft YaHei;font-size:16px;">value</span><span style="font-family:Microsoft YaHei;font-size:16px;">和倍率</span><span style="font-family:Microsoft YaHei;font-size:16px;">mul</span><span style="font-family:Microsoft YaHei;font-size:16px;">。八卦炉发射出的魔法炮是一条无限长的直线形区域，可以视为两条倾斜角为</span></span><span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">α</span><span style="font-family:Microsoft YaHei;font-size:16px;">的平行线之间的区域，平行线之间的距离可以为任意值，如下图所示：</span><span style="font-size:10.5pt;"></span> 
				</p>
				<div style="text-align:center;">
					<img alt="" src="/upload/image/20120808/20120808075810_58680.png"/> 
				</div>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">蓝色部分上下两条长边之间就是这次八卦炉的攻击范围，在蓝色范围内的毛玉</span><span style="font-family:Microsoft YaHei;font-size:16px;">(</span><span style="font-family:Microsoft YaHei;font-size:16px;">红点</span><span style="font-family:Microsoft YaHei;font-size:16px;">)</span><span style="font-family:Microsoft YaHei;font-size:16px;">属于该此被击中的毛玉，如果一个毛玉刚好在边界上也视为被击中。毛玉击中以后就会消失，每次发射八卦炉得到分值是该次击中毛玉的分值和乘上这些毛玉平均的倍率，设该次击中的毛玉集合为</span><span style="font-family:Microsoft YaHei;font-size:16px;">S</span><span style="font-family:Microsoft YaHei;font-size:16px;">，则分值计算公式为</span><span style="font-family:Microsoft YaHei;font-size:16px;">:</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">    </span><span style="font-family:;" calibri";font-size:10.5pt;"=""><span style="font-family:Microsoft YaHei;font-size:16px;">Score = SUM{value[i] | i </span><span style="font-family:Microsoft YaHei;font-size:16px;">属于 </span><span style="font-family:Microsoft YaHei;font-size:16px;">S} * SUM{mul[i] | i </span><span style="font-family:Microsoft YaHei;font-size:16px;">属于 </span><span style="font-family:Microsoft YaHei;font-size:16px;">S} / |S|</span></span><span style="font-family:;" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">其中</span><span style="font-family:Microsoft YaHei;font-size:16px;">|S|</span><span style="font-family:Microsoft YaHei;font-size:16px;">表示</span><span style="font-family:Microsoft YaHei;font-size:16px;">S</span><span style="font-family:Microsoft YaHei;font-size:16px;">的元素个数。魔理沙将会使用若干次八卦炉，直到把所有毛玉全部击中。任意两次攻击的范围均不重叠。最后得到的分值为每次攻击分值之和。现在请你计算出能够得到的最大分值。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #7BA0CD;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">输入格式</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #7BA0CD;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">个整数</span><span style="font-family:Microsoft YaHei;font-size:16px;">N</span><span style="font-family:Microsoft YaHei;font-size:16px;">，表示毛玉个数</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">2..N+1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：每行四个整数</span><span style="font-family:Microsoft YaHei;font-size:16px;">x, y, value, mul</span><span style="font-family:Microsoft YaHei;font-size:16px;">，表示星星的坐标</span><span style="font-family:Microsoft YaHei;font-size:16px;">(x,y)</span><span style="font-family:Microsoft YaHei;font-size:16px;">，以及</span><span style="font-family:Microsoft YaHei;font-size:16px;">value</span><span style="font-family:Microsoft YaHei;font-size:16px;">和</span><span style="font-family:Microsoft YaHei;font-size:16px;">mul</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">N+2</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">个整数</span></span><span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">α</span><span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">，表示倾斜角角度，</span><span style="font-family:Microsoft YaHei;font-size:16px;">0</span><span style="font-family:Microsoft YaHei;font-size:16px;">°到</span><span style="font-family:Microsoft YaHei;font-size:16px;">180</span><span style="font-family:Microsoft YaHei;font-size:16px;">°</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#D3DFEE;border:1pt solid #7BA0CD;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">输出格式</span><span style="font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#D3DFEE;border:1pt solid #7BA0CD;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">个实数，表示最大分值，保留三位小数</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #7BA0CD;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">输入样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #7BA0CD;" colspan="2">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">3</span><span style="font-family:;" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">1 3 3 1</span><span style="font-family:;" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">2 1 2 2</span><span style="font-family:;" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">3 4 2 1</span><span style="font-family:;" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">45</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#D3DFEE;border:1pt solid #7BA0CD;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">输出样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#D3DFEE;border:1pt solid #7BA0CD;" colspan="2">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">9</span><span style="font-family:Microsoft YaHei;font-size:16px;">.333</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #7BA0CD;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;font-weight:bold;"="">数据范围</span><span style="font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #7BA0CD;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">对于</span><span style="font-family:Microsoft YaHei;font-size:16px;">60%</span><span style="font-family:Microsoft YaHei;font-size:16px;">的数据：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= N &lt;= 500</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">对于</span><span style="font-family:Microsoft YaHei;font-size:16px;">100%</span><span style="font-family:Microsoft YaHei;font-size:16px;">的数据：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= N &lt;= 2,000</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">-10,000 &lt;= x,y &lt;= 10,000</span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= value,mul &lt;= 100</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#D3DFEE;border:1pt solid #7BA0CD;">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;font-weight:bold;">注意</span><span style="font-family:;" calibri";font-size:10.5pt;font-weight:bold;"=""></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#D3DFEE;border:1pt solid #7BA0CD;" colspan="2">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" calibri";font-size:10.5pt;"="">π </span><span style="font-family:Microsoft YaHei;font-size:16px;">= 3.1415926</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<img alt="" src="/upload/image/20120808/20120808170327_69133.jpg"/><br/>
