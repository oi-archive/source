
# Description

<div class="content"><p class="MsoNormal" align="center" style="margin: 0cm 0cm 0pt; text-align: center"><span style="font-size: 16pt; font-family: 黑体; mso-hansi-font-family: 黑体"><span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 24pt; mso-char-indent-count: 2.0; mso-char-indent-size: 12.0pt"><span style="font-size: 12pt; font-family: 宋体; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-ascii-font-family: &#39;Times New Roman&#39;">一个有</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">N</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-ascii-font-family: &#39;Times New Roman&#39;">个顶点的简单多边形，画在一个无限大的矩形网格中。对于这样的多边形，只有相邻的两边在它们共同的顶点处相交；没有其它边相交或有接触。该多边形的顶点都在网格的网点上，也就是说，多边形的顶点都是整数坐标。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 24pt; mso-char-indent-count: 2.0; mso-char-indent-size: 12.0pt"><span style="font-size: 12pt; font-family: 宋体; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-ascii-font-family: &#39;Times New Roman&#39;">你的任务是得到严格地处于给定的多边形中的网格线的总长度（这些网格的线段片段在下面的图中着重描出了）。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><div> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">第一行包括一个整数</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">，即多边形的顶点数。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">以下</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">行包括</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">个整数</span><i><span style="font-size: 12pt">x</span></i><span style="font-size: 12pt">和</span><i><span style="font-size: 12pt">y</span></i><span style="font-size: 12pt">，即顶点的坐标。顶点将按顺时针或逆时针顺序给出。所有顶点均不相同，但可能有连续</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">个以上的顶点是在同一条直线上的。</span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">输出只有一行，给出一个带小数部分的数（</span><span style="font-size: 12pt">decimal number</span><span style="font-size: 12pt">）：严格地处于给定的多边形中的网格线的总长度。</span></div>
<div><b><span style="font-size: 14pt">数据范围</span></b></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">3≤ <i>N</i> ≤100 000</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">-500 000 000≤ <i>x</i>, <i>y</i> ≤500 000 000</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">有</span><span style="font-size: 12pt">50</span><span style="font-size: 12pt">分的数据点中，所有多边形的边都处于网格线上。</span></div>
<div><b><span style="font-size: 14pt">评分</span></b></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">若你的输出与标准答案足够接近即可判正确。</span></div>
<div style="text-indent: 24pt"><i><span style="font-size: 12pt">更准确地说：假设你的输出为</span></i><i><span style="font-size: 12pt">L</span></i><i><span style="font-size: 12pt">，标准答案为</span></i><i><span style="font-size: 12pt">R</span></i><i><span style="font-size: 12pt">。那至少以下两个条件至少要有一条成立</span></i><i><span style="font-size: 12pt">:</span></i></div>
<div style="margin: 0cm 0cm 0pt 45.1pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">|<i>L </i>- <i>R</i>|≤R∙10<sup>-6</sup></span><span style="font-size: 12pt">（相对精确）</span></div>
<div style="margin: 0cm 0cm 0pt 45.1pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">|<i>L </i>- <i>R</i>|≤10<sup>-6</sup></span><span style="font-size: 12pt">（绝对精确）</span></div>
<div><b><span style="font-size: 14pt"> </span></b></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
5 1<br/>
2 4<br/>
1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">10.0</span></div>

# Hint

<div class="content"><p></p><div style="text-indent: 24pt"></div><br/>
<div style="text-indent: 24pt"><span style="font-size: 12pt"><img height="251" width="291" alt="" src="/source/bzoj/2349/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNi9iLmpwZw==.jpg"/></span></div><br/>
<div style="text-indent: 24pt"><span style="font-size: 12pt">水平的线段总长度为</span><span style="font-size: 12pt">4/3+8/3=4</span><span style="font-size: 12pt">，垂直的线段总长度为</span><span style="font-size: 12pt">3+2+1=6</span><span style="font-size: 12pt">。总长度为</span><span style="font-size: 12pt">4+6=10</span><span style="font-size: 12pt">。</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

