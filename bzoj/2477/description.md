
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><font face="Times New Roman"><span lang="EN-US">You have a maze </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN">with</span><span lang="EN-US"> obstacles and </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN">non-zero digits</span><span lang="EN-US"> in it:</span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><font face="Times New Roman"><span lang="EN-US"><img height="176" width="366" alt="" src="/source/bzoj/2477/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwOS9hYS5qcGc=.jpg"/></span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Times New Roman"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><font face="Times New Roman"><span lang="EN-US">You can start from any square, walk in the maze, and finally stop at some square. </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN">Each step, you may only walk into one of the <b style="mso-bidi-font-weight: normal"><i style="mso-bidi-font-style: normal"><u>four neighbouring squares (up, down, left, right) </u></i></b>and y</span><span lang="EN-US">ou cannot walk into obstacles</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"> or</span><span lang="EN-US"> </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN">walk into</span><span lang="EN-US"> a square more than once. When you finish, you can get a number by writing down the digits you encounter in the same order as you </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN">meet</span><span lang="EN-US"> them.</span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"> </span><span lang="EN-US">For example, you can get numbers 9784, 4832145 etc. The biggest number you can get is 791452384, shown </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN">in the picture </span><span lang="EN-US">above.</span></font></span><font size="2"><font face="Times New Roman"><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"><o:p></o:p></span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"><o:p><font face="Times New Roman"> </font></o:p></span></span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"><font face="Times New Roman">Your task is to find the biggest number you can get.</font></span></span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"><font size="2"><font face="Times New Roman"><o:p></o:p></font></font></span></p>
<p class="MsoNormal" style="margin: 0cm 54pt 0pt 0cm; tab-stops: 468.0pt 522.0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Times New Roman"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">There will be at most 25 test cases. Each test begins with two integers <i>R</i> and <i>C</i> (2&lt;=<i>R</i>,<i>C</i>&lt;=15, <i>R*C</i>&lt;=30), the number of rows and columns of the maze. The next <i>R</i> rows represent the maze. Each line contains exactly <i>C</i> characters (without leading or trailing spaces), each of them will be either &#39;</font>#</span><font face="Times New Roman"><span lang="EN-US">&#39; or one of the nine non-zero digits. </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN">There will be at least one non-obstacle squares (i.e. squares with a non-zero digit in it) in the maze. </span><span lang="EN-US">The input is terminated by a test case with <i>R</i>=<i>C</i>=0, you should not process it.</span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 54pt 0pt 0cm; tab-stops: 468.0pt 522.0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Times New Roman"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><font face="Times New Roman"><span lang="EN-US">For each test case, print the </span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN">biggest</span><span lang="EN-US"> number you can find, on a single line.</span></font></span><span lang="EN-US" style="mso-fareast-font-family: 宋体; mso-fareast-language: ZH-CN"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 7<br/>
##9784#<br/>
##123##<br/>
##45###<br/>
0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">791452384</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=湖南省第六届大学生计算机程序设计竞赛   ">湖南省第六届大学生计算机程序设计竞赛   </a></p></div>

