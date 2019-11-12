# 题目描述


<table style="padding:0pt 5.4pt;border-collapse:collapse;">
	<tbody>
		<tr>
			<td width="111" valign="top" style="background:#8064A2;border:1pt solid #9F8AB9;" colspan="2">
				<p>
					<span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" font-size:16pt;font-weight:bold;"="">Problem 2</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="552" valign="top" style="background:#8064A2;border:1pt solid #9F8AB9;">
				<p>
					<span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16px;font-weight:bold;">帕秋莉·诺蕾姬</span><span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" font-size:16pt;font-weight:bold;"="">(</span><span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16px;font-weight:bold;">p</span><span style="color: rgb(255, 255, 255); font-family: Microsoft YaHei; font-size: 16px;" font-size:16pt;font-weight:bold;"="">atchouli.cpp/c/pas)</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;font-weight:bold;"="">题目描述</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">在幻想乡，<a href="http://wiki.touhou8.com/index.php?doc-innerlink-%E5%B8%95%E7%A7%8B%E8%8E%89%C2%B7%E8%AF%BA%E8%95%BE%E5%A7%AC.html" target="_blank">帕秋莉·诺蕾姬(</a></span><strong><span style="font-family:Microsoft YaHei;font-size:16px;"><a href="http://wiki.touhou8.com/index.php?doc-innerlink-%E5%B8%95%E7%A7%8B%E8%8E%89%C2%B7%E8%AF%BA%E8%95%BE%E5%A7%AC.html" target="_blank">パチュリー·ノーレッジ)</a></span></strong><span style="font-family:Microsoft YaHei;font-size:16px;">是以宅在图书馆闻名的魔法使。这一天帕秋莉又在考虑如何加强魔法咒语的威力。帕秋莉的魔法咒语是一个仅有大写字母组成的字符串，我们考虑从</span></span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">’</span><span style="font-family:Microsoft YaHei;font-size:16px;">A</span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">’</span><span style="font-family:Microsoft YaHei;font-size:16px;">到</span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">’</span><span style="font-family:Microsoft YaHei;font-size:16px;">Z</span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">’</span><span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">分别表示</span><span style="font-family:Microsoft YaHei;font-size:16px;">0</span><span style="font-family:Microsoft YaHei;font-size:16px;">到</span><span style="font-family:Microsoft YaHei;font-size:16px;">25</span><span style="font-family:Microsoft YaHei;font-size:16px;">的数字，于是这个魔法咒语就可以看作一个</span><span style="font-family:Microsoft YaHei;font-size:16px;">26</span><span style="font-family:Microsoft YaHei;font-size:16px;">进制数。帕秋莉通过研究发现，如果一个魔法咒语所代表的数能够整除</span><span style="font-family:Microsoft YaHei;font-size:16px;">10</span><span style="font-family:Microsoft YaHei;font-size:16px;">进制数</span><span style="font-family:Microsoft YaHei;font-size:16px;">M</span><span style="font-family:Microsoft YaHei;font-size:16px;">的话，就能够发挥最大的威力。若当前的魔法咒语并不能整除</span><span style="font-family:Microsoft YaHei;font-size:16px;">M</span><span style="font-family:Microsoft YaHei;font-size:16px;">，帕秋莉只会将其中两个字符的位置交换，尽量让它能够被</span><span style="font-family:Microsoft YaHei;font-size:16px;">M</span><span style="font-family:Microsoft YaHei;font-size:16px;">整除，当然由于某些咒语比较特殊，无论怎么改变都不能达到这个目的。请你计算出她能否只交换两个字符就让当前咒语被</span><span style="font-family:Microsoft YaHei;font-size:16px;">M</span><span style="font-family:Microsoft YaHei;font-size:16px;">整除。</span><span style="font-family:Microsoft YaHei;font-size:16px;">(</span><span style="font-family:Microsoft YaHei;font-size:16px;">首位的</span></span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">’</span><span style="font-family:Microsoft YaHei;font-size:16px;">A</span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">’</span><span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">为前导</span><span style="font-family:Microsoft YaHei;font-size:16px;">0)</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #9F8AB9;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;font-weight:bold;"="">输入格式</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #9F8AB9;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">个字符串，长度不超过</span><span style="font-family:Microsoft YaHei;font-size:16px;">L</span><span style="font-family:Microsoft YaHei;font-size:16px;">。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">2</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">个正整数，</span><span style="font-family:Microsoft YaHei;font-size:16px;">M</span></span><span style="font-family:;" font-size:10.5pt;"=""> </span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;font-weight:bold;"="">输出格式</span><span style="font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">第</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">行：用空格隔开的</span><span style="font-family:Microsoft YaHei;font-size:16px;">2</span><span style="font-family:Microsoft YaHei;font-size:16px;">个整数，</span></span><span style="font-family:Microsoft YaHei;font-size:16px;">输出时先输位置靠前的那个。</span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">如果存在多种交换方法，输出字典序最小的，比如</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 3</span><span style="font-family:Microsoft YaHei;font-size:16px;">和</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 5</span><span style="font-family:Microsoft YaHei;font-size:16px;">都可以达到目的，就输出</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 3</span><span style="font-family:Microsoft YaHei;font-size:16px;">；</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 3</span><span style="font-family:Microsoft YaHei;font-size:16px;">和</span><span style="font-family:Microsoft YaHei;font-size:16px;">2 4</span><span style="font-family:Microsoft YaHei;font-size:16px;">都行时也输出</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 3</span><span style="font-family:Microsoft YaHei;font-size:16px;">。注意字符串下标从左到右依次为</span><span style="font-family:Microsoft YaHei;font-size:16px;">1</span><span style="font-family:Microsoft YaHei;font-size:16px;">到</span><span style="font-family:Microsoft YaHei;font-size:16px;">L</span><span style="font-family:Microsoft YaHei;font-size:16px;">开始。如果初始魔法咒语已经能够整除</span><span style="font-family:Microsoft YaHei;font-size:16px;">M</span><span style="font-family:Microsoft YaHei;font-size:16px;">，输出</span></span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">”</span><span style="font-family:Microsoft YaHei;font-size:16px;">0 0</span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">”</span><span style="font-family:Microsoft YaHei;font-size:16px;">；若无论如何也不能到达目的输出</span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">”</span><span style="font-family:Microsoft YaHei;font-size:16px;">-1 -1</span><span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;"="">”</span><span style="font-family:Microsoft YaHei;font-size:16px;">。</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #9F8AB9;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;font-weight:bold;"="">输入样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #9F8AB9;" colspan="2">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">PATCHOULI</span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">16</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;font-weight:bold;"="">输出样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;" colspan="2">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:16px;">4 9</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #9F8AB9;">
				<p>
					<span style="font-family: Microsoft YaHei; font-size: 16px;" font-size:10.5pt;font-weight:bold;"="">数据范围</span><span style="font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #9F8AB9;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">对于</span><span style="font-family:Microsoft YaHei;font-size:16px;">30%</span><span style="font-family:Microsoft YaHei;font-size:16px;">的数据：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= L &lt;= 10, 1 &lt;= M &lt;= 100</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">对于</span><span style="font-family:Microsoft YaHei;font-size:16px;">50%</span><span style="font-family:Microsoft YaHei;font-size:16px;">的数据：除前面</span><span style="font-family:Microsoft YaHei;font-size:16px;">30%</span><span style="font-family:Microsoft YaHei;font-size:16px;">外，</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= L &lt;= 500, M = 5</span><span style="font-family:Microsoft YaHei;font-size:16px;">或</span><span style="font-family:Microsoft YaHei;font-size:16px;">25</span><span style="font-family:Microsoft YaHei;font-size:16px;">或</span><span style="font-family:Microsoft YaHei;font-size:16px;">26</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;font-size:16px;">对于</span><span style="font-family:Microsoft YaHei;font-size:16px;">100%</span><span style="font-family:Microsoft YaHei;font-size:16px;">的数据：</span><span style="font-family:Microsoft YaHei;font-size:16px;">1 &lt;= L &lt;= 2,000, 1 &lt;= M &lt;= 200,000</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<img alt="" src="/upload/image/20120808/20120808170426_15965.jpg"/> 
</p>
