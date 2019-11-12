# 题目描述


<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td width="94" valign="center" style="border:0.5000pt solid #FFFFFF;background:#8064A2;">
				<p style="text-align:center;">
					<span style="color:#FFFFFF;font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">Problem 2</span><span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:0.5000pt solid #FFFFFF;background:#8064A2;">
				<p>
					<span style="color:#FFFFFF;font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">铃仙</span><span style="font-family:&#39;Microsoft YaHei&#39;;">•</span><span style="font-family:&#39;Microsoft YaHei&#39;;">优昙华院</span><span style="font-family:&#39;Microsoft YaHei&#39;;">•</span><span style="font-family:&#39;Microsoft YaHei&#39;;">稻叶</span><span style="font-family:&#39;Microsoft YaHei&#39;;">(reisen.cpp/c/pas)</span></span><span style="color:#FFFFFF;font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #8064A2;background:#CCC1D9;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">题目描述</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #8064A2;background:#CCC1D9;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　在幻想乡，<a href="http://wiki.touhou8.com/index.php?doc-view-253.html" target="_blank">铃仙</a></span><a href="http://wiki.touhou8.com/index.php?doc-view-253.html" target="_blank"><span style="font-family:&#39;Microsoft YaHei&#39;;">•</span><span style="font-family:&#39;Microsoft YaHei&#39;;">优昙华院</span><span style="font-family:&#39;Microsoft YaHei&#39;;">•</span></a><span style="font-family:&#39;Microsoft YaHei&#39;;"><a href="http://wiki.touhou8.com/index.php?doc-view-253.html" target="_blank">稻叶(<span style="color:#000000;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:14.399999618530273px;line-height:25px;">レイセン・うどんげいん・イナバ</span>)</a>是从月球逃到永远亭的月兔。同样居住在永远亭的地球兔子因幡帝老是对铃仙恶作剧。某一天，铃仙终于决定要惩罚一下帝，不过首先得在迷途竹林里把帝抓住。永远亭的迷途竹林可以视为一个由</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;">编号</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1..N)</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:&#39;Microsoft YaHei&#39;;">条单向路连接的区域。开始时，帝在路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，每一个单位时间，帝会以相同的概率走到相邻的路口或是停留在当前路口，一条路可以重复走，但是帝不会走回头路，也就是说如果帝从路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">x</span><span style="font-family:&#39;Microsoft YaHei&#39;;">走到了路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">y</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，在到过其他路口前，她一定不会从路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">y</span><span style="font-family:&#39;Microsoft YaHei&#39;;">走回路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">x</span><span style="font-family:&#39;Microsoft YaHei&#39;;">。现在铃仙想知道，在</span><span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:&#39;Microsoft YaHei&#39;;">秒钟以后，在哪个路口抓到帝的可能性最大。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">输入格式</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">行：</span><span style="font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个非负整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N, M, T</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2..M+1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">行：每行</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">u,v</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，表示存在一条从路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">u</span><span style="font-family:&#39;Microsoft YaHei&#39;;">到路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">v</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的单向路</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #8064A2;background:#CCC1D9;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">输出格式</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #8064A2;background:#CCC1D9;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1..N</span><span style="font-family:&#39;Microsoft YaHei&#39;;">行：一个实数，第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;">行表示在路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;">抓到帝的概率，单位为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">%</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，保留</span><span style="font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">位小数</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">输入样例</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">3 4 2</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">1 2</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">1 3</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">2 1</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">2 3</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #8064A2;background:#CCC1D9;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">输出样例</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #8064A2;background:#CCC1D9;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">11.111</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">27.778</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">61.111</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">样例解释</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　时刻</span><span style="font-family:&#39;Microsoft YaHei&#39;;">0: 1(100%)</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　时刻</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1: 1(33.333%) 2(33.333%) 3(33.333%)</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　时刻</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2: 1(11.111%) 2(11.111%+16.667%) 3(33.333%+11.111%+16.667%)</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　在时刻</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">时，只能从路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">走向路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，不可返回路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　若时刻</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">选择停留在路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，时刻</span><span style="font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">时仍然不可以从路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;">走回路口</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，因为尚未走到过其他路口。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center" style="border:1.0000pt solid #8064A2;background:#CCC1D9;">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">数据范围</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top" style="border:1.0000pt solid #8064A2;background:#CCC1D9;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">30%</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N ≤ 5, M ≤ 10, T ≤ 10</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">60%</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N ≤ 10, M ≤ 50, T ≤ 500</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"><span style="font-family:Microsoft YaHei;">　　对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100%</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N ≤ 50, M ≤ 2000, T ≤ 500</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="94" valign="center">
				<p style="text-align:center;">
					<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">注意</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
			<td width="474" valign="top">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">　　输入数据中无重复的边，且不存在自环。</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
