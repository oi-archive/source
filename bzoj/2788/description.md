
# Description

<div class="content"><p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;">有n个正整数X1,X2,...,Xn，再给出m1+m2个限制条件，限制分为两类：</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;">1. 给出a,b (1&lt;=a,b&lt;=n)，要求满足Xa + 1 = Xb</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;">2. 给出c,d (1&lt;=c,d&lt;=n)，要求满足Xc &lt;= Xd</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;">在满足所有限制的条件下，求集合{Xi}大小的最大值。</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px; "><br class="Apple-interchange-newline"/>
第一行三个正整数n, m1, m2 (2&lt;=n&lt;=600, 1&lt;=m1+m2&lt;=100,000)。</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px; ">接下来m1行每行两个正整数a,b (1&lt;=a,b&lt;=n)，表示第一类限制。</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px; ">接下来m2行每行两个正整数c,d (1&lt;=c,d&lt;=n)，表示第二类限制。</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px; "><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px;"><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span style="font-size: medium"><span lang="EN-US"><o:p></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><span style="color: rgb(68, 68, 68); font-family: Tahoma; font-size: medium; line-height: 22px; ">一个正整数，表示集合{Xi}大小的最大值。</span></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px; "><br/>
</span></font></p>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; ">如果无解输出NIE。</p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; tab-stops: 45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt"><span style="font-size: medium"><span lang="EN-US"><o:p></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 2<br/>
<br/>
1 2<br/>
<br/>
3 4<br/>
<br/>
1 4<br/>
<br/>
3 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="line-height: 22px; color: rgb(68, 68, 68); font-family: Tahoma; font-size: medium; text-align: left; ">|X3=1, X1=X4=2, X2=3</span></p><br/>
<p class="MsoNormal" align="left" style="margin-top: 0cm; margin-right: 0cm; margin-bottom: 0pt; margin-left: 0cm; text-align: left; "><font color="#444444" face="Tahoma" size="3"><span style="line-height: 22px; ">这样答案为3。容易发现没有更大的方案。</span></font></p><br/>
<p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 oimaster">鸣谢 oimaster</a></p></div>

