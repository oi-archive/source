# 题目描述


<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td width="94" valign="center" style="border:0.5000pt solid #FFFFFF;background:#4F81BD;">
				<p style="text-align:center;">
					<span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">Problem </span><span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:0.5000pt solid #FFFFFF;background:#4F81BD;">
				<p>
					<span style="color:#FFFFFF;font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;">比那名居天子<span>(tenshi.cpp/c/pas)</span></span><span style="color:#FFFFFF;font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #4F81BD;background:#B8CCE4;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">题目描述</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #4F81BD;background:#B8CCE4;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">在幻想乡，比那名居天子是管理着『要石』的天人。『要石』是能够引发和镇压地震的存在，当然也可以用来改变地形。因为在幻想乡引发地震，而被灵梦等人教训了之后，天子不得不使用『要石』来修复地面。幻想乡可以视为</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">长度为<span>N</span><span>个格子的一条横轴</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">，其中有些格子的土地由于地震被破坏<span>(</span><span>记为</span><span>1)</span><span>，有些格子则没有</span><span>(</span><span>记为</span><span>0)</span><span>。每次使用『要石』，可以把</span></span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">一段长度为<span>L</span><span>的格子全部修复完成</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">(<span>即将</span><span>1</span><span>变为</span><span>0</span><span>，</span><span>L</span><span>覆盖的范围可以超出地图</span><span>)</span><span>，当然</span><span>L</span><span>越大，使用时所花费的灵力也就越多。天子希望</span></span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">最多使用<span>K</span><span>次</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">『要石』就将所有被破坏的土地全部修复完成<span>(</span><span>即将</span><span>1</span><span>全部变为</span><span>0)</span><span>，并且花费尽可能小的灵力。她想知道能够达到这个目的的</span><span>L</span><span>最小是多少。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">输入格式</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>1</span><span>行：</span><span>2</span><span>个整数，</span><span>N, K</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>2</span><span>行：</span><span>1</span><span>个 </span><span>01 </span><span>串，长度为 </span><span>N</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #4F81BD;background:#B8CCE4;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">输出格式</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #4F81BD;background:#B8CCE4;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>1</span><span>行：</span><span>1</span><span>个整数，</span><span>L </span><span>的最小值</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">输入样例</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">10 3</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">0101111011</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #4F81BD;background:#B8CCE4;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">输出样例</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #4F81BD;background:#B8CCE4;">
				<p>
					<span style="font-size:10.5pt;font-family:宋体;">3</span><span style="font-size:10.5pt;font-family:宋体;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">样例解释</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">0</span><span style="color:#0000FF;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">101</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">111011 &gt; 0000</span><span style="color:#0000FF;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">111</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">011 &gt; 00000000</span><span style="color:#0000FF;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">011</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"> &gt; 0000000000</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #4F81BD;background:#B8CCE4;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">数据范围</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #4F81BD;background:#B8CCE4;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">对于 <span>60%</span><span>的数据：</span><span>1 ≤ N,K ≤ 5,000 </span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">对于 <span>100%</span><span>的数据：</span><span>1 ≤ N,K ≤ 500,000</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
