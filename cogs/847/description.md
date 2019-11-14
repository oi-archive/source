# 题目描述


<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">小<span>x</span><span>收到了一份加密的英语考试作文答案。于是他迫切需要将其解密，在经历了很多磨难之后，他得到了部分原文，注意，只是部分原文。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">为了破解加密的作文，小<span>x</span><span>需要做的第一件事情就是找到原文在加密作文中可能第一次出现的位置。加密的作文中的单词和原文中的单词必须是一一对应，每个单词用空格隔开。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">比如加密的作文是：“</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"> </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a a b c d a b c</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">”这里包含了<span>9</span><span>个用空格隔开的单词，部分原文是：“</span></span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">x</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"> </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">y</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">”，这里<span>x</span><span>和</span><span>y</span><span>是不一样的，而在加密的作文由第</span><span>3</span><span>个字符开始的两个单词也是不一样的，所以原文在加密作文中第一次可能出现的位置为</span><span>3</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">再给一个例子，加密的作文时：“</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"> </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">b c x c z z a b c</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">”，部分原文是：“</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">pr</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">v</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">i </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">d</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">r </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">p</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">r</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">v</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">i </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">t</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">r </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">t</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">r</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"> </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">x</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">”，那么部分原文第一次可能出现的位置是<span>3</span><span>，“</span><span>prvi</span><span>”对应“</span><span>c</span><span>”，“</span><span>dr</span><span>”对应“</span><span>x</span><span>”，依次类推。这里原文与加密后的单词肯定是一一对应。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">现在小<span>x</span><span>要你帮助他完成这个任务。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行是加密后的作文全文，全文的字符个数不会超过<span>10^6</span><span>个。每个单词用一个英文空格隔开，最后以一个单独的</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">$</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">结束，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">$</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">不包含在文章中。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第二行是原文的部分句子，部分句子的字符个数不会超过<span>10^6</span><span>个。每个单词用一个英文空格隔开，最后以一个单独的</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">$</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">结束，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">$</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">不包含在文章中。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">保证字符都是小写字符，且都是一个空格隔开。这里的 <span>10^6</span><span>个字符上限不包含空格。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个整数，原文的部分句子在加密的作文中可能第一次出现的位置，这个位置就是加密作文中第一个单词所处在加密文章中位置。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">数据保证有解。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>1</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">kriptogram</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">kriptogram</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p style="margin-left:5.6500pt;text-align:left;">
					<span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"> </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a a b c d a b c $</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="margin-left:5.6500pt;text-align:left;">
					<span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">x</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"> </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">y $</span><span style="font-size:11.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>2</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">kriptogram</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">kriptogram</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p style="text-align:left;">
					<span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"> </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">b c x c z z a b c $</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">pr</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">v</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">i </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">d</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">r </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">p</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">r</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">v</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">i </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">t</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">r </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">t</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">r</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"> </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">x $</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>3</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">kriptogram</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">kriptogram</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p style="text-align:left;">
					<span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">xy</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">z </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">b</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">c </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">b</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">c </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">x</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">y</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">z $</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">ab</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">c </span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">a</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">b</span><span style="font-size:11.5000pt;font-family:&#39;Courier New&#39;;">c $</span><span style="font-size:11.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【数据范围】 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   10% <span>数据保证 加密和原文单词数目 小于等于</span><span>10</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   20% <span>数据保证 加密和原文单词数目 小于等于</span><span>1000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   100%<span>数据如题目描述</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
