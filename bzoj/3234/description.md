
# Description

<div class="content"><div style="margin: 6pt 44.9pt 0pt 18pt; line-height: 19.5pt" align="left"><span style="font-size: medium"><span style="color: black">在一个三维空间中有</span><span style="color: black">N</span><span style="color: black">个立方体，第</span><span style="color: black">i</span><span style="color: black">个立方体占据</span><span style="color: black">x_i1</span><span style="color: black">，</span><span style="color: black">y_i1, z_i1 --- x_i2, y_i2, z_i2</span><span style="color: black">的位置。这</span><span style="color: black">N</span><span style="color: black">个立方体可能有相交，也可能重叠。这</span><span style="color: black">N</span><span style="color: black">个立方体构</span><span style="color: black">成一个大的几何图形。现在求这个几何图形的外表面积</span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div></div>

# Input

<div class="content"><div style="margin: 5pt -3pt 0pt 18pt; line-height: 12pt" align="left"><span style="font-size: medium"><span style="color: black">第一行，一个整数</span><span style="color: black">N</span><span style="color: black">，表示立方体的个数。</span></span></div>
<div style="margin: 6pt 44.9pt 0pt 18pt; line-height: 39pt"><span style="font-size: medium"><span style="color: black">第二行至第</span><span style="color: black">N+1</span><span style="color: black">行，每行</span><span style="color: black">6</span><span style="color: black">个用空格隔开的整数，分别表示</span><span style="color: black">x1,y1,z1,x2,y2,z2. </span></span></div></div>

# Output

<div class="content"><p> </p>
<div style="margin: 5pt -3pt 0pt 18pt; line-height: 12pt" align="left"><span style="font-size: medium"><span style="color: black">一行，一个整数，表示外表面积的大小。</span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 6pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">input 1<br/>
1 <br/>
0  0 0 1 1 1<br/>
 <br/>
 <br/>
<br/>
input 2<br/>
2 <br/>
0  1 0 3 2 1<br/>
1  0 0 2 3 1<br/>
<br/>
 <br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata">output 1<br/>
6 <br/>
<br/>
<br/>
output 2<br/>
22</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 6pt 52.2pt 0pt 18pt; line-height: 19pt; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span lang="EN-US" style="font-size: 12pt; color: black; font-family: &#34;Arial Unicode MS&#34;; mso-font-kerning: 0pt"><font face="Times New Roman">对于第一个样例</font></span></p><br/>
<p class="MsoNormal" style="margin: 6pt 52.2pt 0pt 18pt; line-height: 19pt; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span lang="EN-US" style="font-size: 12pt; color: black; font-family: &#34;Arial Unicode MS&#34;; mso-font-kerning: 0pt"><font face="Times New Roman"><img height="156" alt="" width="134" src="/source/bzoj/3234/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNi8xKDUpLmpwZw==.jpg"/></font></span></p><br/>
<p class="MsoNormal" style="margin: 6pt 52.2pt 0pt 18pt; line-height: 19pt; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span lang="EN-US" style="font-size: 12pt; color: black; font-family: &#34;Arial Unicode MS&#34;; mso-font-kerning: 0pt"><font face="Times New Roman">对于第二个样例</font></span></p><br/>
<p class="MsoNormal" style="margin: 6pt 52.2pt 0pt 18pt; line-height: 19pt; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span lang="EN-US" style="font-size: 12pt; color: black; font-family: &#34;Arial Unicode MS&#34;; mso-font-kerning: 0pt"><font face="Times New Roman"><img height="207" alt="" width="193" src="/source/bzoj/3234/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNi8yKDIpLmpwZw==.jpg"/></font></span></p><br/>
<p class="MsoNormal" style="margin: 6pt 52.2pt 0pt 18pt; line-height: 19pt; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span lang="EN-US" style="font-size: 12pt; color: black; font-family: &#34;Arial Unicode MS&#34;; mso-font-kerning: 0pt"><font face="Times New Roman">1&lt;=N&lt;=200,0&lt;=x_i1,y_i1,z_i1,x_i2,y_i2,z_i2&lt;=200,x_i1&lt;x_i2,y_i1&lt;y_i2,z _i1&lt;z_i2 <o:p></o:p></font></span></p><br/>
<p class="MsoNormal" align="left" style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span lang="EN-US" style="font-size: 10pt; color: black; mso-font-kerning: 0pt; mso-bidi-font-size: 12.0pt"><span style="mso-spacerun: yes"><font face="Times New Roman"> </font></span><o:p></o:p></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢zhonghaoxi提供数据，原数据似有误">鸣谢zhonghaoxi提供数据，原数据似有误</a></p></div>

