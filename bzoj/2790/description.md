
# Description

<div class="content"><p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;">对于两个正整数a、b，这样定义函数d(a,b)：每次操作可以选择一个质数p，将a变成a*p或a/p，</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;">如果选择变成a/p就要保证p是a的约数，d(a,b)表示将a变成b所需的最少操作次数。例如d(69,42)=3。</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;">现在给出n个正整数A1,A2,...,An，对于每个i (1&lt;=i&lt;=n)，求最小的j(1&lt;=j&lt;=n)使得i≠j且d(Ai,Aj)最小。</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><span style="color: rgb(68, 68, 68); font-family: Tahoma; font-size: medium; line-height: 22px; ">第一行一个正整数n (2&lt;=n&lt;=100,000)。第二行n个正整数A1,A2,...,An (Ai&lt;=1,000,000)。</span></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px; "><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 12pt; color: #444444; line-height: 140%; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><span style="color: rgb(68, 68, 68); font-family: Tahoma; font-size: medium; line-height: 22px; ">输出n行，依次表示答案。</span></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px; "><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; tab-stops: 45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt"><span lang="EN-US" style="font-size: 12pt; color: #444444; line-height: 140%; font-family: 宋体; mso-bidi-font-family: 宋体; mso-font-kerning: 0pt"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5<br/>
6<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
1<br/>
2<br/>
1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 oimaster">鸣谢 oimaster</a></p></div>

