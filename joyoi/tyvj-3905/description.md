# 

 
 # 题目背景 
<p>noip2006普及组3&nbsp;</p> 

 
 # 题目描述 
<p>Jam的计数法<br />
【问题描述】<br />
Jam是个喜欢标新立异的科学怪人。他不使用阿拉伯数字计数，而是使用小写英文字母计数，他觉得这样做，会使世界更加丰富多彩。在他的计数法中，每个数字的位数都是相同的（使用相同个数的字母），英文字母按原先的顺序，排在前面的字母小于排在它后面的字母。我们把这样的&ldquo;数字&rdquo;称为Jam数字。在Jam数字中，每个字母互不相同，而且从左到右是严格递增的。每次，Jam还指定使用字母的范围，例如，从2到10，表示只能使用{b,c,d,e,f,g,h,i,j}这些字母。如果再规定位数为5，那么，紧接在Jam数字&ldquo;bdfij&rdquo;之后的数字应该是&ldquo;bdghi&rdquo;。（如果我们用U、V依次表示Jam数字&ldquo;bdfij&rdquo;与&ldquo;bdghi&rdquo;，则U&lt;V&lt;&nbsp;span&gt;，且不存在Jam数字P，使U&lt;P&lt;V&lt;&nbsp;span&gt;）。你的任务是：对于从文件读入的一个Jam数字，按顺序输出紧接在后面的5个Jam数字，如果后面没有那么多Jam数字，那么有几个就输出几个。<br />
【输入文件】<br />
输入文件counting.in&nbsp;有2行，第1行为3个正整数，用一个空格隔开：<br />
s&nbsp;t&nbsp;w<br />
（其中s为所使用的最小的字母的序号，t为所使用的最大的字母的序号。w为数字的位数，这3个数满足：1&le;s&lt;T&lt;&nbsp;span&gt;&le;26,&nbsp;2&le;w&le;t-s&nbsp;）<br />
第2行为具有w个小写字母的字符串，为一个符合要求的Jam数字。<br />
所给的数据都是正确的，不必验证。<br />
【输出文件】<br />
输出文件counting.out&nbsp;最多为5行，为紧接在输入的Jam数字后面的5个Jam数字，如果后面没有那么多Jam数字，那么有几个就输出几个。每行只输出一个Jam数字，是由w个小写字母组成的字符串，不要有多余的空格。<br />
【输入样例】<br />
&nbsp;2&nbsp;10&nbsp;5<br />
&nbsp;bdfij<br />
【输出样例】<br />
bdghi<br />
bdghj<br />
bdgij<br />
bdhij<br />
befgh<br />
&nbsp;</p> 

 
 # 输入格式 
<p>2&nbsp;10&nbsp;5<br />
bdfij</p>

<p>&nbsp;</p> 

 
 # 输出格式 
<p>bdghi<br />
bdghj<br />
bdgij<br />
bdhij<br />
befgh</p> 
