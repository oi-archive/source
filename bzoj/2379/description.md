
# Description

<div class="content"><div><span style="font-size: medium"><span style="color: black">一些蛇覆盖了一个网格。每个格子要么是一个障碍物，要么是蛇的一部分。每条蛇占据了一条折线（拐角处只能水平和竖直连接），且至少占据两个格子。蛇与蛇之间不重叠，蛇也不会与自己重叠。每条蛇还必须满足以下两个条件中的一个：</span></span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -21pt"><span style="font-size: medium"><span style="color: black">1.<span style="font: 7pt &#39;Times New Roman&#39;">         </span></span><span style="color: black">两个端点所在的格子在网格的边界。</span></span></div>
<div style="margin: 0cm 0cm 0pt 39pt; text-indent: -21pt"><span style="font-size: medium"><span style="color: black">2.<span style="font: 7pt &#39;Times New Roman&#39;">         </span></span><span style="color: black">蛇构成一个环，即两个端点相邻（垂直或水平，不能斜着），至少要占据</span><span style="color: black">4</span><span style="color: black">个格子（否则没法形成环）。</span></span></div>
<div><span style="font-size: medium"><span style="color: black">给定一个网格，用</span><span style="color: black">的字符矩阵描述：</span><span style="color: black">’#’</span><span style="color: black">代表障碍物，</span><span style="color: black">’.’</span><span style="color: black">代表空地。在满足前面所述的条件下覆盖所有空地，并使得端点在网格边界（即不构成环）的蛇尽量少。</span></span></div>
<div><span style="font-size: medium"><span style="color: black">例如，以下网格：</span></span></div>
<div align="center"><span style="font-size: medium"><span style="color: black">......</span></span></div>
<div align="center"><span style="font-size: medium"><span style="color: black">.#.##.</span></span></div>
<div align="center"><span style="font-size: medium"><span style="color: black">.#....</span></span></div>
<div align="center"><span style="font-size: medium"><span style="color: black">....#.</span></span></div>
<div align="center"><span style="font-size: medium"><span style="color: black">.##.#.</span></span></div>
<div align="center"><span style="font-size: medium"><span style="color: black">......</span></span></div>
<div><span style="font-size: medium"><span style="color: black">可以由下面三种方案覆盖。还有其它的方案，但是没有仅用一条不构成环的蛇就覆盖整个网格的方案。</span></span></div>
<div></div>
<div><span style="font-size: medium"><span style="color: black"><img height="189" width="440" alt="" src="/source/bzoj/2379/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwMy8xMSgyKS5qcGc=.jpg"/></span></span></div>
<div></div>
<div></div>
<div><span style="font-size: medium"><span style="color: black">
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="color: black; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">给定一个网格的描述，输出最少需要多少条不构成环的蛇来覆盖这个网格。如果不存在能够覆盖网格的方案，输出</span><span lang="EN-US" style="color: black; font-family: Consolas; mso-bidi-font-family: Consolas">-1</span><span style="color: black; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span><span lang="EN-US" style="color: black"><o:p></o:p></span></font></p>
</span></span></div></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="color: black; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">一个字符矩阵，行数和列数不超过</span><span lang="EN-US" style="color: black"><font face="Times New Roman">12</font></span><span style="color: black; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。输入文件中没有多余的空白字符，每行之后都有换行符。</span><span lang="EN-US" style="color: black"><o:p></o:p></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; color: black"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="color: black; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出满足题目要求的那个整数。</span><span lang="EN-US" style="color: black"><o:p></o:p></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; color: black"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">......<br/>
<br/>
.#.##.<br/>
<br/>
.#....<br/>
<br/>
....#.<br/>
<br/>
.##.#.<br/>
<br/>
......<br/>
<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

