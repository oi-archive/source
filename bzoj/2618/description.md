
# Description

<div class="content"><div style="text-indent: 24pt"><span style="font-size: 12pt">逆时针给出</span><i><span style="font-size: 12pt">n</span></i><span style="font-size: 12pt">个凸多边形的顶点坐标，求它们交的面积。例如</span><span style="font-size: 12pt">n=2</span><span style="font-size: 12pt">时，两个凸多边形如下图：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt"><img height="266" alt="" width="238" src="/source/bzoj/2618/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMy8xKDcpLmpwZw==.jpg"/></span></div>
<p></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">则相交部分的面积为</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">5.233</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行有一个整数</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">n</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示凸多边形的个数，以下依次描述各个多边形。第</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">i</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个多边形的第一行包含一个整数</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">m<sub>i</sub></font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示多边形的边数，以下</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">m<sub>i</sub></font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行每行两个整数，逆时针给出各个顶点的坐标。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><o:p><font face="Times New Roman"> </font></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-spacerun: yes"><font face="Times New Roman">    </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出文件仅包含一个实数，表示相交部分的面积，保留三位小数。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><o:p><font face="Times New Roman"> </font></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
6<br/>
-2 0<br/>
-1 -2<br/>
1 -2<br/>
2 0<br/>
1 2<br/>
-1 2<br/>
4<br/>
0 -3<br/>
1 -1<br/>
2 2<br/>
-1 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5.233</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">100%</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的数据满足：</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">2&lt;=<i style="mso-bidi-font-style: normal">n</i>&lt;=10</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">3&lt;=<i style="mso-bidi-font-style: normal">m<sub>i</sub></i>&lt;=50</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，每维坐标为</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">[-1000,1000]</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">内的整数</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p><br/>
<p><span lang="EN-US" style="font-size: 12pt; font-family: &#34;Times New Roman&#34;; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"><br clear="all" style="page-break-before: always; mso-special-character: line-break"/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

