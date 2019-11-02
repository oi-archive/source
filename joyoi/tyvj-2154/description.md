# 

 
 # 题目描述 
<p>小明这些天一直在思考这样一个奇怪而有趣的问题：<br />
&nbsp;&nbsp;&nbsp;&nbsp;在1~N的某个全排列中有多少个连号区间呢？这里所说的连号区间的定义是：<br />
&nbsp;&nbsp;&nbsp;&nbsp;如果区间[L,&nbsp;R]&nbsp;里的所有元素（即此排列的第L个到第R个元素）递增排序后能得到一个长度为R-L+1的&ldquo;连续&rdquo;数列，则称这个区间连号区间。<br />
&nbsp;&nbsp;&nbsp;&nbsp;当N很小的时候，小明可以很快地算出答案，但是当N变大的时候，问题就不是那么简单了，现在小明需要你的帮助。</p> 

 
 # 输入格式 
<p>第一行是一个正整数N&nbsp;(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;50000),&nbsp;表示全排列的规模。<br />
第二行是N个不同的数字Pi(1&nbsp;&lt;=&nbsp;Pi&nbsp;&lt;=&nbsp;N)，&nbsp;表示这N个数字的某一全排列。</p> 

 
 # 输出格式 
<p>输出一个整数，表示不同连号区间的数目。</p> 

 
 # 提示 
<p>输入样例：</p>

<p>4</p>

<p>3&nbsp;2&nbsp;4&nbsp;1</p>

<p>&nbsp;</p>

<p>输出样例：</p>

<p>7</p>

<p>&nbsp;</p> 
