# 题目描述


<h3>
	<span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">Robin是一只极其聪明的鸟，他着迷于人类丰富多彩的语言。经过长时间的摸索，Robin模仿人类的英语创造了鸟类的语言。与英语类似，这种鸟语的基本单位（我们不妨也称其为字母）也是由26个小写英文字母a至z组成的。同时，若干个字母组成一个单词，用来表达一定的意思（和英语一样？！），相邻两个单词由一个空格隔开。Robin为他新发明的鸟语创造了丰富的词汇，并花费大量精力写成一本鸟语字典。正如你所想的那样，Robin想把一些英文的书籍（如《时间简史》、《物种起源》等）翻译成鸟语。但是，这项工作实在是太浩大了，以至于Robin无法完成。聪明的Robin想到使用计算机，他编写了一个自动翻译的程序来翻译这些书籍。但是很快他发现，有很多词汇是他原先所没有想到的。（例如，《时间简史》中的“夸克”，厚厚的鸟语字典里并没有这个词。）对于这种情况，他的自动翻译程序将会不对其做翻译，而是直接放入译文中。</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">下面是一个例子，下表表示字典中只有4个英文单词及其鸟语含义。</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">给出下列一个英文句子：I am a clever bird.</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">翻译后的鸟语语句为：op dg a clever myself.</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">对于没有在字典中出现的单词clever，自动翻译程序直接将其放入译文中。</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">表给定的一个字典</span> 
</p>
<table style="padding:0pt 5.4pt;">
	<tbody>
		<tr>
			<td width="48" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">序号</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">英文</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">鸟语</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="48" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">I</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">op</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="48" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">am</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">dg</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="48" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="48" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">bird</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td width="60" valign="top" style="border:0.5000pt solid #000000;">
				<p>
					<span style="font-size:10.5pt;font-family:&#39;Microsoft YaHei&#39;;">myself</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">现在，Robin已经翻译了一些著作，他希望补充他的鸟语字典。因此，他想知道有多少单词在他的鸟语字典里是没有的，并且，他想统计出在这些没有出现在他的鸟语字典中的单词中，出现次数最多的单词是哪一个。</span> 
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">输入文件的</span><span style="font-family:&#39;Microsoft YaHei&#39;;">第一行为一个正整数n(1≤n≤10000)表示字典内的单词的数目。接下来的n行，每行有一个单词（没有多余空格）,每个单词的长度不超过25个字符。字典中没有重复的单词。</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">然后是一段文本，由若干鸟语（英语）单词组成，相邻两个单词之间用至少一个空格隔开，文本中可能存在某些标点及其他符号。（文本中的单词数目不超过100000；非鸟语单词集(即没出现在鸟语单词集中的单词所组成的集合)中，单词数不超过10000，每个单词的长度不超过25个字符)</span> 
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:Microsoft YaHei;">输出文件的第一行是一个整数m，表示有m个单词没有在鸟语字典中出现。接下来一行t，表示在没有出现在鸟语字典中出现最多的单词有多少个。接下来t行，按字典序输出这些单词。</span> 
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>　　
bird.in
3
ac
jd
opq
ac  jd . jda  opq ae.  ld  jd  opq!　　
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>bird.out
3
3
ae
jda
ld</pre>
