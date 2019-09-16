# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">猫和老鼠在10*10 的方格中运动，例如：<br/>
 *...*.....<br/>
 ......*...<br/>
 ...*...*..<br/>
 ..........<br/>
 ...*.C....<br/>
 *.....*...<br/>
 ...*......<br/>
 ..M......*<br/>
 ...*.*....<br/>
 .*.*......<br/>
 C=猫（CAT）<br/>
 M=老鼠（MOUSE）<br/>
 *=障碍物<br/>
 .=空地<br/>
 猫和老鼠每秒中走一格，如果在某一秒末他们在同一格中，我们称他们“相遇”。<br/>
 注意，“对穿”是不算相遇的。猫和老鼠的移动方式相同：平时沿直线走，下一步如果会走到<br/>
 障碍物上去或者出界，就用1 秒的时间做一个右转90 度。一开始他们都面向北方。<br/>
 编程计算多少秒以后他们相遇。<br/>
</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">10 行，格式如上</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">相遇时间T。如果无解，输出-1。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>*...*.....
 ......*...
 ...*...*..
 ..........
 ...*.C....
 *.....*...
 ...*......
 ..M......*
 ...*.*....
 .*.*......
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>49</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">湖北省NOIP2011寒假集训Day4</span> 
</p>
