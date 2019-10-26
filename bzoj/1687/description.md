
# Description

<div class="content"><div><span style="font-size: medium">    由于牛奶市场的需求，奶牛必须前往城市，但是唯一可用的交通工具是出租车．教会奶牛如何在城市里打的．</span></div>
<div><span style="font-size: medium">    给出一个城市地图，东西街区E(1≤E≤40)，南北街区N(1≤N≤30).制作一个开车指南</span><span style="font-size: medium">给出租车司机，告诉他如何从起点（用S表示）到终点（用E表示）．每一个条目用空格分成两部分，第一个部分是方向（N，E，S，W之一），第二个是一个整数，表示要沿着这个方向开几个十字路口．如果存在多条路线，你应该给出最短的．数据保证，最短的路径存在且唯一．    地图中“+”表示十字路口，道路用“I”和“一”表示．建筑和其他设施用“．”表示．下面是一张地图：</span></div>
<div><span style="font-size: medium"><img height="160" width="162" alt="" src="/source/bzoj/1687/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS80MygyKS5qcGc=.jpg"/></span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">    出租车可以沿着东，北，西，北，东开两个十字路口，以此类推．具体将由样例给出</span></div>
<div></div></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行：两个用空格隔开的整数</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">E.</font></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><span lang="EN-US"><font face="Times New Roman">2N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行：每行有</span><span lang="EN-US"><font face="Times New Roman">2E-I</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个字符，表示地图．</span></font></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">每行有一个表示方向的字母和一个表示要开几个十字路口的数字表示．</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">Sample Input</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><img height="160" width="162" alt="" src="/source/bzoj/1687/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS80MygxKS5qcGc=.jpg"/></span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata">E 1<br/>
N 1<br/>
W 1<br/>
N 1<br/>
E 2<br/>
S 1<br/>
E 3<br/>
S 1<br/>
W 1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

