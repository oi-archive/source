# 

 
 # 题目描述 
<p>阿米巴是小强的好朋友。&nbsp;</p>

<p>在小强眼中，阿米巴是一个作文成绩很高的文艺青年。为了获取考试作文的真谛，小强向阿米巴求教。阿米巴给小强展示了几篇作文，小强觉得这些文章怎么看怎么觉得熟悉，仿佛是某些范文拼拼凑凑而成的。小强不禁向阿米巴投去了疑惑的眼光，却发现阿米巴露出了一个狡黠的微笑。&nbsp;</p>

<p>为了有说服力地向阿米巴展示阿米巴的作文是多么让人觉得&ldquo;眼熟&rdquo;，小强想出了一个评定作文&nbsp;&ldquo;熟悉程度&rdquo;的量化指标：L0.&nbsp;</p>

<p>小强首先将作文转化成一个&nbsp;01&nbsp;串。&nbsp;</p>

<p>之后，小强搜集了各路名家的文章，同样分别转化成&nbsp;01&nbsp;串后，整理出一个包含了&nbsp;M&nbsp;个&nbsp;01&nbsp;串的&ldquo;标准作文库&rdquo;。&nbsp;</p>

<p>小强认为：如果一个&nbsp;01&nbsp;串长度不少于&nbsp;L&nbsp;且在标准作文库中的某个串里出现过（即，它是标准作文库的某个串的一个连续子串），那么它是&ldquo;熟悉&rdquo;的。对于一篇作文（一个&nbsp;01&nbsp;串）A，如果能够把&nbsp;A&nbsp;分割成若干段子串，其中&ldquo;熟悉&rdquo;的子串的长度总和不少于&nbsp;A&nbsp;总长度的&nbsp;90%，那么称&nbsp;A&nbsp;是&ldquo;熟悉的文章&rdquo;。&nbsp;L0&nbsp;是能够让&nbsp;A&nbsp;成为&ldquo;熟悉的文章&rdquo;的所有&nbsp;L&nbsp;的最大值（如果不存在这样的&nbsp;L，那么规定&nbsp;L0&nbsp;=&nbsp;0）。&nbsp;</p>

<p>举个例子：&nbsp;<br />
小强的作文库里包含了如下&nbsp;2&nbsp;个字符串：&nbsp;</p>

<pre class="ckeditor-code cpp">
10110
000001110&nbsp;</pre>

<p>有一篇待考察的作文是：&nbsp;</p>

<pre class="ckeditor-code cpp">
1011001100</pre>

<p>小强计算出这篇作文&nbsp;L&nbsp;的最大值是&nbsp;4，因为待考察的作文可以视作&nbsp;&#39;10110&#39;+&#39;0110&#39;+&#39;0&#39;，其中&#39;10110&#39;和&#39;0110&#39;被判定为&ldquo;熟悉&rdquo;的。而当&nbsp;L&nbsp;=&nbsp;5&nbsp;或是更大的时候，不存在符合题意的分割方法。所以，这篇作文的&nbsp;L0&nbsp;=&nbsp;4。&nbsp;</p>

<p>小强认为阿米巴作文的&nbsp;L0&nbsp;值比其他同学的明显要大。请你帮他验证一下。&nbsp;</p> 

 
 # 输入格式 
<p>第一行是两个整数&nbsp;N,&nbsp;M，表示待检查的作文数量，和小强的标准作文库的行数。</p>

<p>接下来是&nbsp;M&nbsp;行的&nbsp;01&nbsp;串，表示标准作文库。</p>

<p>接下来是&nbsp;N&nbsp;行的&nbsp;01&nbsp;串，表示&nbsp;N&nbsp;篇作文。&nbsp;</p> 

 
 # 输出格式 
<p>包含&nbsp;N&nbsp;行，每一行包含一个整数，表示该篇作文的&nbsp;L0&nbsp;值。</p> 

 
 # 提示 
<h3>数据规模</h3>

<p>对于&nbsp;30%的测试数据，输入文件的长度不超过&nbsp;1000&nbsp;字节。&nbsp;</p>

<p>对于&nbsp;50%的测试数据，输入文件的长度不超过&nbsp;61000&nbsp;字节。</p>

<p>对于&nbsp;80%的测试数据，输入文件的长度不超过&nbsp;250000&nbsp;字节。</p>

<p>对于&nbsp;100%的测试数据，输入文件的长度不超过&nbsp;1100000&nbsp;字节。&nbsp;</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>1 2
10110
000001110
1011001100
</td><td>4</td></tr></table>
