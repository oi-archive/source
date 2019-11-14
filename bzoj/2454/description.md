
# Description

<div class="content"><p style="text-indent: 21pt"><span style="position: relative; top: 3pt">从前，森林里有三只寂寞的兔子。 </span><span style="font-family: &#39;宋体&#39;; position: relative; top: 3pt; mso-text-raise: -3.0000pt; mso-spacerun: &#39;yes&#39;">它们平时搞<font face="Times New Roman">OI</font><font face="宋体">，做题做累了就开始玩游戏。</font></span><span style="font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-text-raise: -3.0000pt; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-family: &#39;宋体&#39;; position: relative; top: 3pt; mso-text-raise: -3.0000pt; mso-spacerun: &#39;yes&#39;">游戏在一个无限长的由树桩组成的直线上进行，相邻两树桩距离相同，为了方便表示，兔子们把树桩标号为…，<font face="Times New Roman">-2</font><font face="宋体">，</font><font face="Times New Roman">-1</font><font face="宋体">，</font><font face="Times New Roman">0</font><font face="宋体">，</font><font face="Times New Roman">1</font><font face="宋体">，</font><font face="Times New Roman">2</font><font face="宋体">，…。游戏开始时，三只兔子站在不同的三个树桩上。游戏中，兔子可以跳过另一只兔子到达轴对称的那个树桩上。</font></span><span style="font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-text-raise: -3.0000pt; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-text-raise: -3.0000pt; mso-spacerun: &#39;yes&#39;"><img height="285" alt="" width="550" src="/source/bzoj/2454/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwOS8xMS5qcGc=.jpg"/></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-family: &#39;Times New Roman&#39;; position: relative; top: 3pt; mso-text-raise: -3.0000pt; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-size: medium"><span style="font-family: 宋体; position: relative; top: 3pt; mso-text-raise: -3.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">但是，兔子不能落在已有兔子的树桩，也不能一次跃过两只兔子。</span></span><span lang="EN-US" style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-size: medium"><span style="font-family: 宋体; position: relative; top: 3pt; mso-text-raise: -3.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">出于</span><span lang="EN-US" style="position: relative; top: 3pt; mso-text-raise: -3.0pt">OIer</span><span style="font-family: 宋体; position: relative; top: 3pt; mso-text-raise: -3.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的本性，兔子们想探究一下，从游戏的初始局面，恰跳</span><span lang="EN-US" style="position: relative; top: 3pt; mso-text-raise: -3.0pt">K</span><span style="font-family: 宋体; position: relative; top: 3pt; mso-text-raise: -3.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">次到达某个特定局面，有多少种不同的跳跃顺序。</span></span><span lang="EN-US" style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; line-height: 150%"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输入一行，前三个数字，表示三只兔子的起始位置。接下来三个数字，表示终止局面的位置。最后一个数字，表示<font face="Times New Roman">K</font><font face="宋体">。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; line-height: 150%"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; line-height: 150%"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输出不同方案数模<font face="Times New Roman">1,000,000,007</font><font face="宋体">的结果。</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 21pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">0 5 8 0 8 11 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>100%数据满足1≤k≤100，位置标号的绝对值不超过10^18。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

