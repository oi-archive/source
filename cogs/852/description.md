# 题目描述


<p>
	<span style="font-family:宋体;">【题目描述】</span> 
</p>
<p>
	<span style="font-family:宋体;">一个字符串</span><span>S</span><span style="font-family:宋体;">的</span><span>RLE-size</span><span style="font-family:宋体;">定义为：将</span><span>S</span><span style="font-family:宋体;">分为最少的段数</span><span>k</span><span style="font-family:宋体;">，使得每段里的字符都相同，则</span><span>k</span><span style="font-family:宋体;">即为</span><span>S</span><span style="font-family:宋体;">的</span><span>RLE-size</span><span style="font-family:宋体;">。比如</span><span>“aabbaa</span><span style="font-family:宋体;">”的</span><span>RLE-size</span><span style="font-family:宋体;">为</span><span>3</span><span style="font-family:宋体;">，</span><span>&#34;aabab&#34;</span><span style="font-family:宋体;">的</span><span>RLE-size</span><span style="font-family:宋体;">为</span><span>4</span><span style="font-family:宋体;">。</span> 
</p>
<p>
	<span style="font-family:宋体;">然后现在给你一个只有变量和操作符组成的后缀表达式</span><span>T</span><span style="font-family:宋体;">，请你将它重新排列成一个新的后缀表达式</span><span>T&#39;</span><span style="font-family:宋体;">，使得</span><span>T</span><span style="font-family:宋体;">与</span><span>T&#39;</span><span style="font-family:宋体;">等价，而且</span><span>T&#39;</span><span style="font-family:宋体;">的</span><span>RLE-size</span><span style="font-family:宋体;">最小。</span> 
</p>
<p>
	<span style="font-family:宋体;">注意所有的操作符都满足交换律和结合律，而且所有的变量都为小写字母，所有的操作符都为</span><span>&#39;+&#39;, &#39;*&#39;, &#39;#&#39;, &#39;!&#39;, &#39;@&#39;, &#39;$&#39;, &#39;%&#39; &#39;^&#39;</span><span style="font-family:宋体;">中一个。保证所有表达式合法。</span> 
</p>
<p>
	<span style="font-family:宋体;">【输入格式】</span> 
</p>
<p>
	<span style="font-family:宋体;">一行字符串，表示后缀表达式</span><span>T</span> 
</p>
<p>
	<span style="font-family:宋体;">【输出格式】</span> 
</p>
<p>
	<span style="font-family:宋体;">一行一个整数，表示</span><span>T&#39;</span><span style="font-family:宋体;">的最小</span><span>RLE-size</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输入</span><span>1</span><span style="font-family:宋体;">】</span> 
</p>
<p>
	<span>af+b*cd**</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输出</span><span>1</span><span style="font-family:宋体;">】</span> 
</p>
<p>
	<span>7</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输入</span><span>2</span><span style="font-family:宋体;">】</span> 
</p>
<p>
	<span>xy*x*y*x*y*</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输出</span><span>2</span><span style="font-family:宋体;">】</span> 
</p>
<p>
	<span>3</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例解释】</span> 
</p>
<p>
	<span style="font-family:宋体;">对于样例</span><span>1</span><span style="font-family:宋体;">，原输入表达式可重新排列为</span><span>daf+bc***</span><span style="font-family:宋体;">，其</span><span>RLE-size</span><span style="font-family:宋体;">为</span><span>7</span><span style="font-family:宋体;">，而且原输入表达式是等价的。</span> 
</p>
<p>
	<span style="font-family:宋体;">对于样例</span><span>2</span><span style="font-family:宋体;">，原输入表达式可重新排列为</span><span>xxxyyy*****</span><span style="font-family:宋体;">或者</span><span>yyyxxx*****</span> 
</p>
<p>
	<span style="font-family:宋体;">【数据规模】</span> 
</p>
<p>
	<span style="font-family:宋体;">对于</span><span>20%</span><span style="font-family:宋体;">的数据，</span><span>T</span><span style="font-family:宋体;">的长度不超过</span><span>10</span> 
</p>
<p>
	<span style="font-family:宋体;">对于</span><span>100%</span><span style="font-family:宋体;">的数据，</span><span>T</span><span style="font-family:宋体;">的长度不超过</span><span>2500</span> 
</p>
<p>
	<span style="font-family:宋体;">【时限】</span> 
</p>
<p>
	<span>2s</span> 
</p>
