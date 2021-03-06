# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
阿米巴是小强的好朋友。
</p>
<p>
在小强眼中，阿米巴是一个作文成绩很高的文艺青年。为了获取考试作文的真谛，小强向阿米巴求教。阿米巴给小强展示了几篇作文，小强觉得这些文章怎么看怎么觉得熟悉，仿佛是某些范文拼拼凑凑而成的。小强不禁向阿米巴投去了疑惑的眼光，却发现阿米巴露出了一个狡黠的微笑。
</p>
<p>
为了有说服力地向阿米巴展示阿米巴的作文是多么让人觉得“眼熟”，小强想出了一个评定作文 “熟悉程度”的量化指标：L0.
</p>
<p>
小强首先将作文转化成一个01串。
</p>
<p>
之后，小强搜集了各路名家的文章，同样分别转化成01串后，整理出一个包含了M个01串的“标准作文库”。
</p>
<p>
小强认为：如果一个01串长度不少于L且在标准作文库中的某个串里出现过（即，它是标准作文库的某个串的一个连续子串），那么它是“熟悉”的。对于一篇作文（一个01串）A，如果能够把A分割成若干段子串，其中“熟悉”的子串的长度总和不少于A总长度的90%，那么称A是“熟悉的文章”。 L0是能够让A成为“熟悉的文章”的所有L的最大值（如果不存在这样的L，那么规定L0 = 0）。
</p>
<p>
举个例子：
</p>
<p>
小强的作文库里包含了如下2个字符串：
</p>
<p>
10110
</p>
<p>
000001110
</p>
<p>
有一篇待考察的作文是：
</p>
<p>
1011001100
</p>
<p>
小强计算出这篇作文L的最大值是4，因为待考察的作文可以视作&#39;10110&#39;+&#39;0110&#39;+&#39;0&#39;，其中&#39;10110&#39;和&#39;0110&#39;被判定为“熟悉”的。而当L = 5或是更大的时候，不存在符合题意的分割方法。所以，这篇作文的L0 = 4。
</p>
<p>
小强认为阿米巴作文的L0值比其他同学的明显要大。请你帮他验证一下。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入第一行是两个整数 N, M，表示待检查的作文数量，和小强的标准作文库的行数。
</p>
<p>
接下来是M行的01串，表示标准作文库。
</p>
<p>
接下来是N行的01串，表示N篇作文。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出N行，每一行包含一个整数，表示该篇作文的L0值。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
1 2
</p>

<p>
10110
</p>

<p>
000001110
</p>

<p>
1011001100
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
对于30%的测试数据，输入文件的长度不超过1000字节。
</p>
<p>
对于50%的测试数据，输入文件的长度不超过61000字节。
</p>
<p>
对于80%的测试数据，输入文件的长度不超过250000字节。
</p>
<p>
对于100%的测试数据，输入文件的长度不超过1100000字节。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
http://www.tsinsen.com/A1346
</p>
