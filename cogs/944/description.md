# 题目描述


<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td width="94" valign="center" style="border:0.5000pt solid #FFFFFF;background:#C0504D;">
				<p style="text-align:center;">
					<span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">Problem </span><span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">3</span><span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:0.5000pt solid #FFFFFF;background:#C0504D;">
				<p>
					<span style="color:#FFFFFF;font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;">藤原妹红<span>(mokou.cpp/c/pas)</span></span><span style="color:#FFFFFF;font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #C0504D;background:#E5B9B7;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">题目描述</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #C0504D;background:#E5B9B7;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">在幻想乡，</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><a href="http://wiki.touhou8.com/index.php?doc-view-217.html">藤原妹红(<span>ふじわらのもこう</span><span>)</span></a></span>是拥有不老不死能力的人类。虽然不喜欢与人们交流，妹红仍然保护着误入迷途竹林村民。由于算得上是幻想乡最强的人类，对于她而言，迷途竹林的单向道路亦可以逆行。在妹红眼中，迷途竹林可以视为一个由<span>N</span><span>个路口</span><span>(</span><span>编号</span><span>1..N)</span><span>，</span><span>M</span><span>条</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">不同长度双向路</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">连接的区域。妹红所在的红之自警队为了方便在迷途竹林中行动，绘制了一张特殊的迷途竹林地图，这张地图上只保留了<span>N-1</span><span>条道路，</span></span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">这些道路保证了任意两个路口间有且仅有一条路径，并且满足所有保留的道路长度之和最小</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">，我们称这些道路为</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">『自警队道路』</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">。现在妹红打算在其中一个</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">连接有多条『自警队道路』的路口</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">设立根据地，当去掉根据地这个根据地所在路口后，就会出现某些路口间无法通过『自警队道路』相互连通的情况，我们认为这时</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">仍然能够通过『自警队道路』连通的路口属于同一个『区域』。</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">妹红希望最后每个『区域』的『自警队道路』总长尽可能平均，请计算出她应该选择哪一个路口作为根据地。</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">下例中红色的路口为妹红选择的根据地，实线边表示『自警队道路』，绿色虚线边表示非『自警队道路』，数字表示边权，『自警队道路』中相同颜色的实线边代表属于同一个『区域』：</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:宋体;"><img src="http://192.168.1.139/upload/image/20120809/20120809153141_86387.png" width="415" height="281" alt=""/></span><span style="font-size:10.5pt;font-family:宋体;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">(<span>尽可能平均即权重最小，设每一块『区域』的路线总长为</span><span>Length[i]</span><span>，平均路线长度为</span><span>Avg=SUM{Length[i]}/</span><span>区域数，权重</span><span>d=∑( (Length[i]-Avg)^2 ) )</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
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
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>1</span><span>行：</span><span>2</span><span>个正整数</span><span>N,M</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>2..M+1</span><span>行：每行</span><span>2</span><span>个整数</span><span>u,v</span><span>和</span><span>1</span><span>个实数</span><span>len</span><span>，表示</span><span>u,v</span><span>之间存在长度为</span><span>len</span><span>的边</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #C0504D;background:#E5B9B7;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">输出格式</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #C0504D;background:#E5B9B7;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>1</span><span>行：</span><span>1</span><span>个整数，最后选择的路口编号，存在多个可选路口时选择编号小的</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
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
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">3 3</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">3 1 5</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">3 2 4</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">1 2 3</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #C0504D;background:#E5B9B7;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">输出样例</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #C0504D;background:#E5B9B7;">
				<p>
					<span style="font-size:10.5pt;font-family:宋体;">2</span><span style="font-size:10.5pt;font-family:宋体;"></span> 
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
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">妹红的『自警队道路』为<span>(1,2)</span><span>和</span><span>(2,3)</span><span>。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">只能选择<span>2</span><span>作为根据地，产生的两个区域</span><span>Length[i]</span><span>分别为</span><span>3</span><span>和</span><span>4</span><span>。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">所以方差为：<span>(4-3.5)^2 + (3-3.5)^2 = 0.5</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #C0504D;background:#E5B9B7;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">数据范围</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #C0504D;background:#E5B9B7;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">对于<span>60%</span><span>的数据：</span><span>3 ≤ N ≤ 2,000</span><span>，</span><span>N-1 ≤ M ≤ 50,000</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">对于<span>100%</span><span>的数据：</span><span>3 ≤ N ≤ 40,000</span><span>，</span><span>N-1 ≤ M ≤ 200,000</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">对于<span>100%</span><span>的数据：</span><span>0 &lt; len ≤ 100,000,000</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">注意</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">保证不存在相同距离的线路，两个路口间可能出现多条路径，且任意点对间至少存在一条路径。</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<br/>
