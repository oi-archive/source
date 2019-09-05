# 题目描述


<p>
	</p><table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
		<tbody>
			<tr>
				<td width="94" valign="center" style="border:0.5000pt solid #FFFFFF;background:#9BBB59;">
					<p style="text-align:center;">
						<span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">Problem </span><span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="color:#FFFFFF;font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
				<td width="" valign="top" style="border:0.5000pt solid #FFFFFF;background:#9BBB59;">
					<p>
						<span style="color:#FFFFFF;font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;">稗田阿求<span>(akyuu.cpp/c/pas)</span></span><span style="color:#FFFFFF;font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="94" valign="center" style="border:1.0000pt solid #9BBB59;background:#D7E3BC;">
					<p style="text-align:center;">
						<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">题目描述</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
				<td width="474" valign="top" style="border:1.0000pt solid #9BBB59;background:#D7E3BC;">
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">在幻想乡，稗田乙女是负责书写《幻想乡缘起》的家族。由于需要代代相传关于幻想乡的记忆，稗田乙女采用了一些特殊的记录方式。对于相同重复的文字，稗田乙女会用一个数字来代替，然后用一个数列来表示一个段文字。</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">比如<span>1</span><span>代表</span><span>&#34;A&#34;</span><span>，</span><span>2</span><span>代表</span><span>&#34;C&#34;</span><span>，那么</span><span>{1,2}</span><span>就代表</span><span>&#34;AC&#34;</span><span>，</span><span>{2,1,2}</span><span>就代表</span><span>&#34;CAC&#34;</span><span>。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">不过由于年代过于久远，到<a href="http://wiki.touhou8.com/index.php?doc-view-186.html" target="_blank"><span style="font-family:&#39;Times New Roman&#39;;font-size:14.399999618530273px;line-height:16.799999237060547px;background-color:#D7E3BC;">稗田</span>阿求(ひえだの あきゅう)</a>时已经是第九代稗田乙女，所以难免会出现错误。现在阿求有<span>N</span><span>个数字</span><span>(1..N)</span><span>和</span><span>N</span><span>个字符</span><span>(&#39;A&#39;..</span><span>第</span><span>N</span><span>个字母</span><span>)</span><span>，以及一些以前传承下来的</span><span>M</span><span>组文字段和对应的数列。</span></span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">每一组文字段和数列相互对应，文字的第<span>i</span><span>个字符对应着数列的第</span><span>i</span><span>项。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">阿求想要知道怎样安排<span>N</span><span>个数字和字符的对应关系，能够使组数尽可能多的文字段和数列组合满足该对应关系。</span></span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">数字和字符间一一对应，不会出现多对一或一对多的情况。</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
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
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>1</span><span>行：</span><span>2</span><span>个正整数</span><span>N, M</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>2..2*M+1</span><span>行：每</span><span>2</span><span>行为一组，第</span><span>1</span><span>行为文字段落，第</span><span>2</span><span>行为数列。保证文字段落的字符数</span><span>L</span><span>等于数列数字个数</span><span>L</span><span>，且均在</span><span>1..N</span><span>。文字段落只包含大写字母</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="94" valign="center" style="border:1.0000pt solid #9BBB59;background:#D7E3BC;">
					<p style="text-align:center;">
						<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">输出格式</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
				<td width="474" valign="top" style="border:1.0000pt solid #9BBB59;background:#D7E3BC;">
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">第<span>1</span><span>行：最多能够匹配的文字段落和数列组合数量</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
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
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">ACCA</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">1 3 3 1 </span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">AAC</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">2 2 1</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">BCBC</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">3 1 3 1</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="94" valign="center" style="border:1.0000pt solid #9BBB59;background:#D7E3BC;">
					<p style="text-align:center;">
						<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">输出样例</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
				<td width="474" valign="top" style="border:1.0000pt solid #9BBB59;background:#D7E3BC;">
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
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">当<span>A=2,B=3,C=1</span><span>时第</span><span>2</span><span>、</span><span>3</span><span>字符串和数列组合满足对应关系。</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="94" valign="center" style="border:1.0000pt solid #9BBB59;background:#D7E3BC;">
					<p style="text-align:center;">
						<span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">数据范围</span><span style="font-weight:bold;font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
				<td width="474" valign="top" style="border:1.0000pt solid #9BBB59;background:#D7E3BC;">
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">对于<span>60%</span><span>的数据： </span><span>1 ≤ N ≤ 10</span><span>，</span><span>1 ≤ M ≤ 20</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">对于<span>100%</span><span>的数据：</span><span>1 ≤ N ≤ 26</span><span>，</span><span>1 ≤ M ≤ 60</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">对于<span>100%</span><span>的数据：</span><span>1 ≤ L ≤ 100</span></span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
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
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">保证每一组文字段和数列组合均合法；</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;">在一组文字段和数列组合里面不会出现多个字符对一个数字，或是一个字符对多个数字的情况。</span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:10.5pt;font-family:&#39;Times New Roman&#39;;"></span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
<span><span style="line-height:normal;"><img src="/upload/image/20120809/20120809165446_56782.png" alt=""/><br/>
</span></span> 
<p></p>
