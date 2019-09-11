# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<div>
<span style="text-indent:23.25pt;font-family:arial, verdana, helvetica, sans-serif;font-size:12pt;">你有一个N*N的棋盘，每个格子内有一个整数，初始时的时候全部为0，现在需要维护两种操作：</span> 
</div>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:23.25pt;font-family:arial, verdana, helvetica, sans-serif;font-size:18px;">
<span lang="EN-US" style="font-family:宋体;font-size:12pt;"><o:p style="font-family:arial, verdana, helvetica, sans-serif;"> </o:p></span> 
</p>
<table class="MsoNormalTable" style="border:currentColor;border-image:none;font-family:arial, verdana, helvetica, sans-serif;border-collapse:collapse;" border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="189" valign="top" style="padding:0cm 5.4pt;border:1pt solid black;border-image:none;width:142pt;font-family:arial, verdana, helvetica, sans-serif;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span style="font-family:宋体;font-size:12pt;">命令<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span> 
</p>
</td>
<td width="189" valign="top" style="border-color:black black black #ECE9D8;padding:0cm 5.4pt;width:142.05pt;font-family:arial, verdana, helvetica, sans-serif;border-top-width:1pt;border-right-width:1pt;border-bottom-width:1pt;border-top-style:solid;border-right-style:solid;border-bottom-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span style="font-family:宋体;font-size:12pt;">参数限制<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span> 
</p>
</td>
<td width="189" valign="top" style="border-color:black black black #ECE9D8;padding:0cm 5.4pt;width:142.05pt;font-family:arial, verdana, helvetica, sans-serif;border-top-width:1pt;border-right-width:1pt;border-bottom-width:1pt;border-top-style:solid;border-right-style:solid;border-bottom-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span style="font-family:宋体;font-size:12pt;">内容<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span> 
</p>
</td>
</tr>
<tr>
<td width="189" valign="top" style="border-color:#ECE9D8 black black;padding:0cm 5.4pt;width:142pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-left-width:1pt;border-right-style:solid;border-bottom-style:solid;border-left-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:宋体;font-size:12pt;">1 x y A<o:p style="font-family:arial, verdana, helvetica, sans-serif;"></o:p></span> 
</p>
</td>
<td width="189" valign="top" style="border-color:#ECE9D8 black black #ECE9D8;padding:0cm 5.4pt;width:142.05pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-right-style:solid;border-bottom-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:宋体;font-size:12pt;">1&lt;=x,y&lt;=N</span><span style="font-family:宋体;font-size:12pt;">，<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;">A</span>是正整数<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span> 
</p>
</td>
<td width="189" valign="top" style="border-color:#ECE9D8 black black #ECE9D8;padding:0cm 5.4pt;width:142.05pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-right-style:solid;border-bottom-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span style="font-family:宋体;font-size:12pt;">将格子<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;">x,y</span>里的数字加上<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;">A<o:p></o:p></span></span> 
</p>
</td>
</tr>
<tr>
<td width="189" valign="top" style="border-color:#ECE9D8 black black;padding:0cm 5.4pt;width:142pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-left-width:1pt;border-right-style:solid;border-bottom-style:solid;border-left-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:宋体;font-size:12pt;">2 x<sub style="font-family:arial, verdana, helvetica, sans-serif;">1</sub> y<sub style="font-family:arial, verdana, helvetica, sans-serif;">1</sub> x<sub style="font-family:arial, verdana, helvetica, sans-serif;">2</sub> y<sub style="font-family:arial, verdana, helvetica, sans-serif;">2</sub><o:p style="font-family:arial, verdana, helvetica, sans-serif;"></o:p></span> 
</p>
</td>
<td width="189" valign="top" style="border-color:#ECE9D8 black black #ECE9D8;padding:0cm 5.4pt;width:142.05pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-right-style:solid;border-bottom-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:宋体;font-size:12pt;">1&lt;=x<sub style="font-family:arial, verdana, helvetica, sans-serif;">1</sub>&lt;= x<sub style="font-family:arial, verdana, helvetica, sans-serif;">2</sub>&lt;=N<o:p style="font-family:arial, verdana, helvetica, sans-serif;"></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:宋体;font-size:12pt;">1&lt;=y<sub style="font-family:arial, verdana, helvetica, sans-serif;">1</sub>&lt;= y<sub style="font-family:arial, verdana, helvetica, sans-serif;">2</sub>&lt;=N<o:p style="font-family:arial, verdana, helvetica, sans-serif;"></o:p></span> 
</p>
</td>
<td width="189" valign="top" style="border-color:#ECE9D8 black black #ECE9D8;padding:0cm 5.4pt;width:142.05pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-right-style:solid;border-bottom-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span style="font-family:宋体;font-size:12pt;">输出<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;">x<sub>1</sub> y<sub>1</sub> x<sub>2</sub> y<sub>2</sub></span>这个矩形内的数字和<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span> 
</p>
</td>
</tr>
<tr>
<td width="189" valign="top" style="border-color:#ECE9D8 black black;padding:0cm 5.4pt;width:142pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-left-width:1pt;border-right-style:solid;border-bottom-style:solid;border-left-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:宋体;font-size:12pt;">3<o:p style="font-family:arial, verdana, helvetica, sans-serif;"></o:p></span> 
</p>
</td>
<td width="189" valign="top" style="border-color:#ECE9D8 black black #ECE9D8;padding:0cm 5.4pt;width:142.05pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-right-style:solid;border-bottom-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span style="font-family:宋体;font-size:12pt;">无<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span> 
</p>
</td>
<td width="189" valign="top" style="border-color:#ECE9D8 black black #ECE9D8;padding:0cm 5.4pt;width:142.05pt;font-family:arial, verdana, helvetica, sans-serif;border-right-width:1pt;border-bottom-width:1pt;border-right-style:solid;border-bottom-style:solid;background-color:transparent;">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span style="font-family:宋体;font-size:12pt;">终止程序<span lang="EN-US" style="font-family:arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span> 
</p>
</td>
</tr>
</tbody>
</table>
<div>
</div>
<div>
</div>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<div>
输入文件第一行一个正整数N。
</div>
<div>
<div>
接下来每行一个操作。每条命令除第一个数字之外，
</div>
<div>
均要异或上一次输出的答案last_ans，初始时last_ans=0。
</div>
<div>
</div>
</div>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<div>
对于每个2操作，输出一个对应的答案。
</div>
</div>
<h3>
【样例输入】
</h3>
<pre>4
  1 2 3 3
  2 1 1 3 3
  1 1 1 1
  2 1 1 0 7
  3</pre>
<h3>
【样例输出】
</h3>
<pre>3
  5</pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<br/>
</p>
<div>
数据规模和约定
</div>
<br/>
<div>
1&lt;=N&lt;=500000,操作数不超过200000个，内存限制20M，保证答案在int范围内并且解码之后数据仍合法。
</div>
<br/>
<div>
样例解释见OJ2683
</div>
<br/>
<div>
</div>
<br/>
<div>
新加数据一组，但未重测----2015.05.24
</div>
<br/>
<div>
</div>
<p>
<br/>
</p>
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search=By wjy1998">By wjy1998</a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=4066">耒阳大世界（衡阳八中） OJ 4066</a>
