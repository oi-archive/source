# 题目描述


<p align="center" style="text-align:center;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"><span style="background-color:#9933E5;color:#FFE500;">福州NOIP2010</span><span style="background-color:#9933E5;color:#FFE500;">培训 Day2</span></span></b>
</p>
<p align="center" style="text-align:center;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">数字游戏</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">(bds)</span></b> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【题目描述】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">有这么一个游戏：</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">写出一个</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">～</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的排列</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">a[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，然后每次将相邻两个数相加，构成新的序列，再对新序列进行这样的操作，显然每次构成的序列都比上一次的序列长度少</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，直到只剩下一个数字位置。下面是一个例子：</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">    3  
1   2   4</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">      4  
3   6</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">        7  
9</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">         16</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">最后得到</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">16</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">这样一个数字。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">现在想要倒着玩这样一个游戏，如果知道</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，知道最后得到的数字的大小</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">sum</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，请你求出最初序列</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">a[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，为</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">～</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的一个排列。若答案有多种可能，则输出字典序最小的那一个。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输入格式】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输入文件</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">bds.in</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的第</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">行为两个正整数</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">sum</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输出格式】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输出文件</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">bds.out</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">包括</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">行，对于每个询问输出答案。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【样例输入】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">4 16</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【样例输出】</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">3 1 2 4</span> 
</p>
<p style="text-indent:20.25pt;">
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【数据规模】</span><span></span> 
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">         </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">对于</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">40%</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的数据，</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">≤</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">7</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">；</span><span></span> 
</p>
<p>
	<span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">         </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">对于</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">80%</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的数据，</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">≤</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">10</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">；</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">   对于</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">100%</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的数据，</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">≤</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">12</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">sum</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">≤</span><span style="font-size:18px;font-family:&#39;Microsoft YaHei&#39;;">12345</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，且保证一定有解。</span><span></span> 
</p>
