

# 问题描述



# 输入


<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行是加密后的作文全文，全文的字符个数不会超过<span>10^6</span><span>个。每个单词用一个英文空格隔开，最后以一个单独的</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">$</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">结束，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">$</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">不包含在文章中。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第二行是原文的部分句子，部分句子的字符个数不会超过<span>10^6</span><span>个。每个单词用一个英文空格隔开，最后以一个单独的</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">$</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">结束，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">$</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">不包含在文章中。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">保证字符都是小写字符，且都是一个空格隔开。这里的 <span>10^6</span><span>个字符上限不包含空格。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>

# 输出


<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个整数，原文的部分句子在加密的作文中可能第一次出现的位置，这个位置就是加密作文中第一个单词所处在加密文章中位置。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>

# 输入输出样例<span>1</span><span>


<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				
# 输入输出样例<span>2</span><span>


<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				
# 输入输出样例<span>3</span><span>


<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				
# 数据范围


<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   10% <span>数据保证 加密和原文单词数目 小于等于</span><span>10</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   20% <span>数据保证 加密和原文单词数目 小于等于</span><span>1000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   100%<span>数据如题目描述</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
