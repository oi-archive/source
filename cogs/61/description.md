# 题目描述


<p>
<!--[if gte mso 9]>Normal07.8 磅02falsefalsefalseMicrosoftInternetExplorer4<![endif]--><!--[if gte mso 9]><![endif]-->
<!--[if gte mso 10]>
<![endif]-->
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">鼹鼠是一种很喜欢挖洞的动物，但每过一定的时间，它还是喜欢把头探出到地面上来透透气的。</span><span style="font-size:12pt;"></span> 
</p>
<p style="text-indent:24pt;">
<span style="font-family:宋体;">根据这个特点阿</span><span>Q</span><span style="font-family:宋体;">编写了一个打鼹鼠的游戏：在一个</span><span>n*n</span><span style="font-family:宋体;">的网格中，在某些时刻鼹鼠会在某一个网格探出头来透透气。你可以控制一个机器人来打鼹鼠，如果</span><span>i</span><span style="font-family:宋体;">时刻鼹鼠在某个网格中出现，而机器人也处于同一网格的话，那么这个鼹鼠就会被机器人打死。而机器人每一时刻只能够移动一格或停留在原地不动。机器人的移动是指从当前所处的网格移向相邻的网格，即从坐标为（</span><span>i,j</span><span style="font-family:宋体;">）的网格移向</span><span>(i-1, j),(i+1, j),(i,j-1),(i,j+1)</span><span style="font-family:宋体;">四个网格，机器人不能走出整个</span><span>n*n</span><span style="font-family:宋体;">的网格。游戏开始时，你可以自由选定机器人的初始位置。</span> 
</p>
<h2>
<span style="font-family:黑体;">【任务描述】</span> 
</h2>
<p>
<span style="font-family:宋体;">现在你知道在一段时间内，鼹鼠出现的时间和地点，希望你编写一个程序使机器人在这一段时间内打死尽可能多的鼹鼠。</span> 
</p>
<h2>
<span style="font-family:黑体;">【输入格式】</span> 
</h2>
<p>
<span style="font-family:宋体;">你将从文件</span><span>input.txt</span><span style="font-family:宋体;">中读入数据，文件第一行为</span><span>n</span><span style="font-family:宋体;">（</span><span>n&lt;=1000</span><span style="font-family:宋体;">）</span><span>, m</span><span style="font-family:宋体;">（</span><span>m&lt;=10000</span><span style="font-family:宋体;">），其中</span><span>m</span><span style="font-family:宋体;">表示在这一段时间内出现的鼹鼠的个数，接下来的</span><span>m</span><span style="font-family:宋体;">行每行有三个数据</span><span>time,x,y</span><span style="font-family:宋体;">表示有一只鼹鼠在游戏开始后</span><span>time</span><span style="font-family:宋体;">个时刻，在第</span><span>x</span><span style="font-family:宋体;">行第</span><span>y</span><span style="font-family:宋体;">个网格里出现了一只鼹鼠。</span><span>Time</span><span style="font-family:宋体;">按递增的顺序给出。注意同一时刻可能出现多只鼹鼠，但同一时刻同一地点只可能出现一只鼹鼠。</span> 
</p>
<h3>
<span style="font-family:宋体;">【输入样例】</span> 
</h3>
<table width="204" style="border:currentColor;width:153pt;border-collapse:collapse;" border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="204" valign="top" style="border:1pt solid windowtext;">
<p>
<span>2 2</span> 
</p>
<p>
<span>1 1 1</span> 
</p>
<p>
<span>2 2 2</span> 
</p>
</td>
</tr>
</tbody>
</table>
<h2>
<span style="font-family:黑体;">【输出格式】</span> 
</h2>
<p style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">输出文件</span><span style="font-size:12pt;">output.txt</span><span style="font-family:宋体;font-size:12pt;">中仅包含一个正整数，表示被打死鼹鼠的最大数目。</span><span style="font-size:12pt;"></span> 
</p>
<h3>
<span style="font-family:宋体;">【输出样例】</span> 
</h3>
<table width="204" style="border:currentColor;width:153pt;border-collapse:collapse;" border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="204" valign="top" style="border:1pt solid windowtext;">
<p>
<span>1</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
<span style="font-size:12pt;"> </span> 
</p>
<h2>
<span style="font-family:黑体;">【运行限制】</span> 
</h2>
<p>
<span><span> </span></span><span style="font-family:宋体;">运行时限：</span><span>1</span><span style="font-family:宋体;">秒钟</span> 
</p>
<h2>
<span style="font-family:黑体;">【评分方法】</span> 
</h2>
<p style="text-indent:24pt;">
<span style="font-family:宋体;">本题目一共有十个测试点，每个测试点的分数为总分数的</span><span>10%</span><span style="font-family:宋体;">。对于每个测试点来说，如果你给出的答案正确，那么你将得到该测试点全部的分数，否则得</span><span>0</span><span style="font-family:宋体;">分。</span> 
</p>
<p>
<br/>
</p>
