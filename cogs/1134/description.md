# 题目描述


<p>
	<span style="font-family:宋体;"><b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">问题描述</span></b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">】</span></span> 
</p>
<p>
	<span style="font-family:宋体;"></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 在生物学应用中，经常要比较两个(或更多)不同有机体的DNA。一个DNA螺旋由一串被称为基的分子组成，可能的基包括腺嘌呤(adenine)、鸟嘌呤(guanine)、胞嘧啶(cytosine)和胸腺嘧啶(thymine)。分别以它们的首字母来代表这些基，一个DNA螺旋可以表示为在有穷集合{A，C，G，T}上的一个串。例如，一个有机体的DNA可能为s1= 
ACCGGTCGAGTGCGCGGAAGCCGGCCGAA，而另一个有机体的DNA可能为S2=GTCGTTCGGAATGCCGTTGCTCTGTAAA.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 将两个DNA螺旋作比较的一个目的就是要确定这两个螺旋有多么&#34;相似&#34;，也就是关于这两个有机体的某些度量有多么接近。相似度可以而且已经用很多不同方式来定义。例如，我们可以说两个DNA螺旋相似，如果其中一个是另一个的子串。在我们的例子中，S1或S2都不是另一方的子串。或者，我们可以说两个螺旋相似，如果把其中一个转换成另一个所需改变的数量很小。另外一个度量螺旋S1和S2相似度的方式是找出第三个螺旋S3，在S3中的基也都出现在S1和S2中；而且这些基必须是以相同的顺序出现，但是不必要是连续的。能找到的S3越长，S1和S2就越相似。在我们的例子中，最长的螺旋S3是GTCGTCGGAAGCCGGCCGAA</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行：基因串1</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第二行： 基因串2</span> 
</p>
<p>
	<span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行：最长的基因串的长度</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第二行：最长基因串</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果有多个，输出字典序最小的。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入样例】</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件名：lcsdna</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">.in</span></span> 
</p>
<pre>ACCGGTCGAGTGCGCGGAAGCCGGCCGAA
GTCGTTCGGAATGCCGTTGCTCTGTAAA
</pre>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件名：</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">lcsdna.out</span></span> 
</p>
<pre>20
GTCGTCGGAAGCCGGCCGAA</pre>
