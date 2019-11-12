# 题目描述


<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">J</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">zyz<span>要举行校草选举了，一共有</span><span>N</span><span>位自命不凡的帅哥报名参加，标号分别为</span><span>1..N</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">校草的评比按四项属性来评，属性的编号分别是<span>A</span><span>，</span><span>B</span><span>，</span><span>C</span><span>，</span><span>D</span><span>，你可以理解为身高，体重，文艺，眼神……。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">现在我们已经完成了各个属性的排名，即每个校草按照<span>A</span><span>属性排序后的名次，按照</span><span>B</span><span>属性排序后的名次，依次类推，保证排名不会有同一名次的。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">因为帅哥太多，现在组委会决定淘汰一些候选人，淘汰的标准是：如果某位帅哥<span>X</span><span>有不少于三个属性都低于某位帅哥</span><span>Y</span><span>，那么我们认为帅哥</span><span>X</span><span>将被淘汰。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">现在对于八卦的小<span>x</span><span>想知道，被淘汰的帅哥有多少个且分别是谁？</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行一个正整数<span>N</span><span>，表示</span><span>N</span><span>为帅哥，编号分别是</span><span>1..N</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来<span>N</span><span>行，每行</span><span>4</span><span>个正整数：</span><span>Ai,Bi,Ci,Di</span><span>。</span><span>Ai</span><span>表示第</span><span>i</span><span>为帅哥在属性</span><span>A</span><span>里的排名是几，依次类推</span><span>Bi</span><span>表示帅哥</span><span>i</span><span>在属性</span><span>B</span><span>里的排名……</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">所有排名的取值是<span>1..N</span><span>的排列，也就是说属性的排名不会有同名次的。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行一个整数<span>M</span><span>，表示</span><span>M</span><span>位帅哥将被淘汰。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来<span>M</span><span>行，每行一个整数</span><span>Xi</span><span>，表示被淘汰的帅哥的编号。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
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
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">hjjhvf</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">hjjhvf</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">6</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 1 2 6</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 3 3 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 4 1 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4 2 6 5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 6 5 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">6 5 4 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">6</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">{2 4 5 6<span>号帅哥都被</span><span>1</span><span>号帅哥淘汰</span><span>}</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【数据范围】 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   对于<span>20%</span><span>的数据 </span><span>N&lt;=3000</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   对于所有的数据  <span>N&lt;=100000</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:16.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span> 
</p>
