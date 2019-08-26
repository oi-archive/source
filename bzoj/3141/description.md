
# Description

<div class="content"><p><img height="752" width="776" alt="" src="source/bzoj/3141/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNC8xKDUpLmpwZw==.jpg"/></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行为两个空格隔开的正整数n, m，表示旅行的城市数与旅行所花的月数。接下来n行，其中第 i行包含两个空格隔开的整数Ai和Bi，Ai表示他第i个去的城市编号。Bi为0或1;如果Bi=0则表示城市Ai没有小L想去的景点，如果Bi=1则表示城市Ai有小L想去的景点，<br/>
Ai两两不同且有1&lt;=Ai&lt;=N,即{Ai}为1,2....N的一个排列。<br/>
例如{2,1,3,4...N}<br/>
N&lt;=500000,M&lt;=200000<br/>
</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">t仅包括一行，包含m个空格隔开的正整数X1,X2...Xm，t仅包括一行，包含m个空格隔开的正整数X1,X2...Xm，为给小L安排的旅行计划对应的路线。为给小L安排的旅行计划对应的路线。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">8  3<br/>
2  0<br/>
3  1<br/>
4  1<br/>
1  0<br/>
5  0<br/>
6  1<br/>
7  1<br/>
8  0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 6 8<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" align="left" style="margin: 0.25pt 52.35pt 0pt 18pt; line-height: 16pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">第</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">1</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">个月得到</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">2</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">点快乐值与</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">2</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">点疲劳值，第</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">2</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">个月得到</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">1</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">点快乐值与</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">1</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">点疲劳值，第</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">3 </font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">个月得到</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">1</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">点快乐值与</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">1</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">点疲劳值。</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">3</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">个月中疲劳值与快乐值差的最大值为</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">0</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">，达到所有方</span><span style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> </font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">案最小值。</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> <o:p></o:p></font></span></p><br/>
<p class="MsoNormal" align="left" style="margin: 0.25pt -1.5pt 0pt 39pt; line-height: 12.75pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">可行方案有：</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> <o:p></o:p></font></span></p><br/>
<p class="MsoNormal" align="left" style="margin: 1.25pt -1.5pt 0pt 39pt; text-indent: 0cm; line-height: 12.75pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none; mso-list: l1 level1 lfo1"><font face="Times New Roman"><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt; mso-fareast-font-family: &#39;Times New Roman&#39;"><span style="mso-list: Ignore">1 </span></span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><span style="mso-spacerun: yes"> </span>6 8<o:p></o:p></span></font></p><br/>
<p class="MsoNormal" align="left" style="margin: 0.25pt -1.5pt 0pt 39pt; text-indent: 0cm; line-height: 12.75pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none; mso-list: l0 level1 lfo2"><font face="Times New Roman"><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt; mso-fareast-font-family: &#39;Times New Roman&#39;"><span style="mso-list: Ignore">3 </span></span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><span style="mso-spacerun: yes"> </span>6 8<o:p></o:p></span></font></p><br/>
<p class="MsoNormal" align="left" style="margin: 1.25pt -1.5pt 0pt 39pt; text-indent: 0cm; line-height: 12.75pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none; mso-list: l0 level1 lfo2"><font face="Times New Roman"><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt; mso-fareast-font-family: &#39;Times New Roman&#39;"><span style="mso-list: Ignore">3 </span></span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><span style="mso-spacerun: yes"> </span>1 8<o:p></o:p></span></font></p><br/>
<p class="MsoNormal" align="left" style="margin: 1.25pt -1.5pt 0pt 39pt; line-height: 12.75pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">其中</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">1 6 8</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">字典序最小。</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> <o:p></o:p></font></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

