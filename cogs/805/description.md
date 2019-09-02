# 题目描述


<p>
	<span></span> 
</p>
<p style="margin-left:11.95pt;">
	<span></span> 
</p>
<h3>
	<i><span style="font-family:Microsoft YaHei;">Problem 1  </span></i><span style="font-family:Microsoft YaHei;">食物中毒 </span><i><span style="font-family:Microsoft YaHei;">(</span></i><i><span style="font-family:Microsoft YaHei;">m</span></i><i><span style="font-family:Microsoft YaHei;">e</span></i><i><span style="font-family:Microsoft YaHei;">d</span></i><i><span style="font-family:Microsoft YaHei;">icine.</span></i><i><span style="font-family:Microsoft YaHei;">pas/c/cpp)</span></i> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.8pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">背景</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.75pt;text-indent:10.55pt;">
	<i><span style="font-family:Microsoft YaHei;">WZOI</span></i><span style="font-family:Microsoft YaHei;">的小组成员今天集体食物中毒，什么事情也不能干了，这是一件十分可怕的事。幸
亏</span><i><span style="font-family:Microsoft YaHei;">WZOI</span></i><span style="font-family:Microsoft YaHei;">的</span><i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">同志十分在行化学，他可以马上制作出解药来……</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.8pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">问题描述</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.75pt;text-align:justify;text-indent:10.55pt;">
	<i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">经过一段时间的研究发现，要解这种毒需要一种特殊的药物。不幸的是，这种药物在市面上不存在，没有办法</span><i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">只好亲自制得这种药物。它含有</span><i><span style="font-family:Microsoft YaHei;">M</span></i><span style="font-family:Microsoft YaHei;">种化学物质</span><i><span style="font-family:Microsoft YaHei;">A</span></i><i><span style="font-family:Microsoft YaHei;">1</span></i><i><span style="font-family:Microsoft YaHei;">,A</span></i><i><span style="font-family:Microsoft YaHei;">2</span></i><i><span style="font-family:Microsoft YaHei;">,</span></i><span style="font-family:Microsoft YaHei;">⋯</span><i><span style="font-family:Microsoft YaHei;">,A</span></i><i><span style="font-family:Microsoft YaHei;">M</span></i><span style="font-family:Microsoft YaHei;">。现 在</span><i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">的手上有N种药材(每种药材只有一种)，每种药材含有若干种化学物质(</span><i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">他有一种
机器，只要将药材放入机器，就能制得相应的药物)。</span> 
</p>
<p style="margin-left:10.8pt;text-indent:10.55pt;">
	<i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">需要你的帮助，他希望你能帮他选取若干种药材，用这些选取的药材制作出</span><i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">需要 的药物。由于这些化学物质是有毒的，因此你选出来的药物，必须含有这M种化学物质。</span> 
</p>
<p style="margin-left:10.75pt;text-indent:10.6pt;">
	<span style="font-family:Microsoft YaHei;">有一点需要注意：根据中医以毒攻毒的理论，两个相同的化学物质在一起，它们的药性会
同时消失变为一种无毒物质(大多情况下这种无毒物质会挥发掉，也就是说这种化学物质消 失了)。比如说药材1有化学物质1、2，药材2有化学物质1、3，那么如果药材1和药材2混合， 你得到的药物会含有化学物质2、3。</span> 
</p>
<p style="margin-left:21.3pt;">
	<i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">问你，需要选用那些药材可以制得他想要的药物？</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.8pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">输入格式</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.75pt;text-indent:10.55pt;">
	<span style="font-family:Microsoft YaHei;">本题每个测试点存在多组数据，每组输入数据第1行包含两个整数</span><i><span style="font-family:Microsoft YaHei;">N</span></i><span style="font-family:Microsoft YaHei;">和</span><i><span style="font-family:Microsoft YaHei;">M</span></i><span style="font-family:Microsoft YaHei;">，表示</span><i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">拥有的 药材数目和他所需药物所含的化学物质的种类数目；</span> 
</p>
<p style="margin-left:10.75pt;text-indent:10.6pt;">
	<span style="font-family:Microsoft YaHei;">第2行共有</span><i><span style="font-family:Microsoft YaHei;">M</span></i><span style="font-family:Microsoft YaHei;">个整数，分别表示M中化学物质的编号，用1~50之间的数字编号(输入数据保 证同一种化学物质不会被描述多次)；</span> 
</p>
<p style="margin-left:21.3pt;">
	<span style="font-family:Microsoft YaHei;">第3行到第</span><i><span style="font-family:Microsoft YaHei;">N</span></i><i><span style="font-family:Microsoft YaHei;">+2</span></i><span style="font-family:Microsoft YaHei;">行，每行包含若干个数。第i+2行的第一个数为</span><i><span style="font-family:Microsoft YaHei;">M</span></i><i><span style="font-family:Microsoft YaHei;">i</span></i><span style="font-family:Microsoft YaHei;">，表示药材i包含Mi种化</span> 
</p>
<p style="margin-left:10.7pt;">
	<span style="font-family:Microsoft YaHei;">学物质，接下来</span><i><span style="font-family:Microsoft YaHei;">M</span></i><i><span style="font-family:Microsoft YaHei;">i</span></i><span style="font-family:Microsoft YaHei;">个数，描述药材i含有的化学物质的编号，用1~50之间的数字编号(同一种</span> 
</p>
<p style="margin-left:10.7pt;">
	<span style="font-family:Microsoft YaHei;">化学物质可能会被描述多次)。</span> 
</p>
<p style="margin-left:21.25pt;">
	<span style="font-family:Microsoft YaHei;">每组输入数据用一个空行隔开。</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">输出格式</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.75pt;text-indent:10.55pt;">
	<span style="font-family:Microsoft YaHei;">对于每组数据输出一行，如果用这些药材可以制得</span><i><span style="font-family:Microsoft YaHei;">Bqc</span></i><span style="font-family:Microsoft YaHei;">需要的药物，那么输出“Possible”； 否则输出“Impossible”，不包含引号。</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:10.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">样例输入输出</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<table border="0" cellspacing="0" cellpadding="0">
	<tbody>
		<tr>
			<td width="284" valign="top" style="border:solid black 1.0pt;">
				<p style="margin-left:5.25pt;">
					<i><span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">m</span><span style="font-family:&#39;Microsoft YaHei&#39;;">e</span><span style="font-family:Microsoft YaHei;">d</span><span style="font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-family:Microsoft YaHei;">cin</span><span style="font-family:&#39;Microsoft YaHei&#39;;">e</span><span style="font-family:Microsoft YaHei;">.in</span></span></i><span style="font-size:12.0pt;font-family:;"></span> 
				</p>
			</td>
			<td width="284" valign="top" style="border:solid black 1.0pt;">
				<p style="margin-left:5.25pt;">
					<i><span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">m</span><span style="font-family:&#39;Microsoft YaHei&#39;;">e</span><span style="font-family:Microsoft YaHei;">d</span><span style="font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-family:Microsoft YaHei;">cin</span><span style="font-family:&#39;Microsoft YaHei&#39;;">e</span><span style="font-family:Microsoft YaHei;">.out</span></span></i><span style="font-size:12.0pt;font-family:;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="284" valign="top" style="border:solid black 1.0pt;">
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">2</span><span> </span><span style="font-family:Microsoft YaHei;">2</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">2</span><span> </span><span style="font-family:Microsoft YaHei;">3</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">2</span><span> </span><span style="font-family:Microsoft YaHei;">1 5</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">2</span><span> </span><span style="font-family:Microsoft YaHei;">1 3</span></span> 
				</p>
				<p style="margin-left:0cm;">
					<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">3</span><span> </span><span style="font-family:Microsoft YaHei;">3</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">1</span><span> </span><span style="font-family:Microsoft YaHei;">3 4</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">4</span><span> </span><span style="font-family:Microsoft YaHei;">2 3 4 1</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">1</span><span> </span><span style="font-family:Microsoft YaHei;">4</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:10.5pt;">2 2 1</span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;"> </span></span> 
				</p>
				<p style="margin-left:0cm;">
					<br/>
				</p>
				<p style="margin-left:5.75pt;">
					4 4
				</p>
				<p style="margin-left:5.75pt;">
					1
2 3 4
				</p>
				<p style="margin-left:5.75pt;">
					3
1 3 4
				</p>
				<p style="margin-left:5.75pt;">
					3 1 4 5
				</p>
				<p style="margin-left:5.75pt;">
					1
2
				</p>
				<p style="margin-left:5.75pt;">
					2
2 3
				</p>
<br/>
				<p>
					<br/>
				</p>
			</td>
			<td width="284" valign="top" style="border:solid black 1.0pt;">
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">I</span><span style="font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-family:Microsoft YaHei;">p</span><span style="font-family:&#39;Microsoft YaHei&#39;;">o</span><span style="font-family:Microsoft YaHei;">s</span><span style="font-family:&#39;Microsoft YaHei&#39;;">s</span><span style="font-family:Microsoft YaHei;">ible</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">P</span><span style="font-family:&#39;Microsoft YaHei&#39;;">o</span><span style="font-family:Microsoft YaHei;">ssible</span></span> 
				</p>
				<p style="margin-left:5.25pt;">
					<span style="font-size:10.5pt;font-family:;"><span style="font-family:Microsoft YaHei;">P</span><span style="font-family:&#39;Microsoft YaHei&#39;;">o</span><span style="font-family:Microsoft YaHei;">ssible</span></span><span style="font-size:12.0pt;font-family:;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p style="margin-left:0cm;">
	<br/>
</p>
<span></span> 
<p>
	<br/>
</p>
<p style="margin-left:5.8pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">样例解释</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:16.3pt;">
	<span style="font-family:Microsoft YaHei;">对于样例的第三组数据，可行的方案有选取 1、3 和选取 2、4.</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:5.8pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">数据规模</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:5.75pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><i><span style="font-family:Microsoft YaHei;">30%</span></i><span style="font-family:Microsoft YaHei;">的数据，</span><i><span style="font-family:Microsoft YaHei;">N</span></i><i><span style="font-family:Microsoft YaHei;">≤</span></i><i><span style="font-family:Microsoft YaHei;">10</span></i><span style="font-family:Microsoft YaHei;">，</span><i><span style="font-family:Microsoft YaHei;">M</span></i><i><span style="font-family:Microsoft YaHei;">≤</span></i><i><span style="font-family:Microsoft YaHei;">20</span></i><span style="font-family:Microsoft YaHei;">； </span> 
</p>
<p style="margin-left:5.75pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><i><span style="font-family:Microsoft YaHei;">50%</span></i><span style="font-family:Microsoft YaHei;">的数据，</span><i><span style="font-family:Microsoft YaHei;">N</span></i><i><span style="font-family:Microsoft YaHei;">≤</span></i><i><span style="font-family:Microsoft YaHei;">20</span></i><span style="font-family:Microsoft YaHei;">，</span><i><span style="font-family:Microsoft YaHei;">M</span></i><i><span style="font-family:Microsoft YaHei;">≤</span></i><i><span style="font-family:Microsoft YaHei;">40</span></i><span style="font-family:Microsoft YaHei;">； 对于</span><i><span style="font-family:Microsoft YaHei;">100%</span></i><span style="font-family:Microsoft YaHei;">的数据，</span><i><span style="font-family:Microsoft YaHei;">N</span></i><i><span style="font-family:Microsoft YaHei;">≤</span></i><i><span style="font-family:Microsoft YaHei;">20</span></i><span style="font-family:Microsoft YaHei;">，</span><i><span style="font-family:Microsoft YaHei;">M</span></i><i><span style="font-family:Microsoft YaHei;">≤</span></i><i><span style="font-family:Microsoft YaHei;">50</span></i><span style="font-family:Microsoft YaHei;">；</span> 
</p>
<p style="margin-left:5.75pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><i><span style="font-family:Microsoft YaHei;">100%</span></i><span style="font-family:Microsoft YaHei;">的数据，</span><i><span style="font-family:Microsoft YaHei;">M</span></i><i><span style="font-family:Microsoft YaHei;">i</span></i><i><span style="font-family:Microsoft YaHei;">≤</span></i><i><span style="font-family:Microsoft YaHei;">50</span></i><span style="font-family:Microsoft YaHei;">。 保证测试数据的组数不超过100。</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:5.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">时间限制</span> 
</p>
<p style="margin-left:5.75pt;">
	<span style="font-family:Microsoft YaHei;">1s</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:5.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:24px;">提示</span> 
</p>
<p style="margin-left:0cm;">
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p style="margin-left:16.3pt;">
	<span></span><span style="font-family:Microsoft YaHei;">同一种化学物质被描述偶数次，那么说明这种物质不存在；否则这种物质存在。</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;"> </span><span></span> 
</p>
