
# Description

<div class="content"><p style="margin: 0cm 0cm 0pt; text-indent: 21pt" class="MsoNormal"><v:shapetype path="m,l,21600r21600,l21600,xe" o:spt="202" coordsize="21600,21600" id="_x0000_t202"><v:stroke joinstyle="miter"></v:stroke><v:path o:connecttype="rect" gradientshapeok="t"></v:path></v:shapetype><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt">传说中，南极有一片广阔的冰原，在冰原下藏有史前文明的遗址。整个冰原被横竖划分成了很多个大小相等的方格。在这个冰原上有<span lang="EN-US">N</span>个大小不等的矩形冰山，这些巨大的冰山有着和南极一样古老的历史，每个矩形冰山至少占据一个方格，且其必定完整地占据方格。冰山和冰山之间不会重叠，也不会有边或点相连。以下两种情况均是不可能出现的：</span></p>
<p style="margin: 0cm 0cm 0pt; text-indent: 21pt" class="MsoNormal"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt"><img alt="" src="/source/bzoj/2541/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMi8xKDEpLmpwZw==.jpg"/></span></p>
<p style="margin: 0cm 0cm 0pt; text-indent: 21pt" class="MsoNormal"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt"><span lang="EN-US"><o:p></o:p></span></span></p>
<p></p>
<p></p>
<p style="margin: 0cm 0cm 0pt; text-indent: 21pt" class="MsoNormal"></p>
<p></p>
<p style="margin: 0cm 0cm 0pt; text-indent: 21pt" class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt">ACM</span><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt">探险队在经过多年准备之后决定在这个冰原上寻找遗址。根据他们掌握的资料，在这个冰原上一个大小为一格的深洞中，藏有一个由史前人类制作的开关。而唯一可以打开这个开关的是一个占据接近一格的可移动的小冰块。显然，在南极是不可能有这样小的独立冰块的，所以这块冰块也一定是史前文明的产物。他们在想办法把这个冰块推到洞里去，这样就可以打开一条通往冰原底部的通道，发掘史前文明的秘密。冰块的起始位置与深洞的位置均不和任何冰山相邻。</span><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt">这个冰原上的冰面和冰山都是完全光滑的，轻轻的推动冰块就可以使这个冰块向前滑行，直到撞到一座冰山就在它的边上停下来。冰块可以穿过冰面上所有没有冰山的区域，也可以从两座冰山之间穿过（见下图）。冰块只能沿网格方向推动。</span></p>
<p style="margin: 0cm 0cm 0pt; text-indent: 21pt" class="MsoNormal"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt"><span lang="EN-US"><o:p><img alt="" src="/source/bzoj/2541/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMi8yKDEpLmpwZw==.jpg"/></o:p></span></span></p>
<p><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt"><span lang="EN-US"> </span></span></p>
<p style="margin: 0cm 0cm 0pt; text-indent: 21pt" class="MsoNormal"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt">请你帮助他们以最少的推动次数将冰块推入深洞中。<span lang="EN-US"><o:p></o:p></span></span></p>
<p></p>
<p style="margin: 0cm 0cm 0pt; text-indent: 21pt" class="MsoNormal"></p></div>

# Input

<div class="content"><p style="margin: 0cm 0cm 0pt" class="MsoNormal"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt">输入文件第一行为冰山的个数<span lang="EN-US">N (1&lt;=N&lt;=4000)</span>，第二行为冰块开始所在的方格坐标<span lang="EN-US">X<sub>1</sub>,Y<sub>1</sub></span>，第三行为深洞所在的方格坐标<span lang="EN-US">X<sub>2</sub>,Y<sub>2</sub></span>，以下<span lang="EN-US">N</span>行每行有四个数，分别是每个冰山所占的格子左上角和右下角坐标<span lang="EN-US">X<sub>i1</sub>,Y<sub>i1</sub>,X<sub>i2</sub>,Y<sub>i2</sub><o:p></o:p></span></span></p>
<p style="margin: 0cm 0cm 0pt" class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt"><o:p> </o:p></span></p></div>

# Output

<div class="content"><p style="margin: 0cm 0cm 0pt" class="MsoNormal"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-size: 10.0pt">输出文件仅包含一个整数，为最少推动冰块的次数。如果无法将冰块推入深洞中，则输出<span lang="EN-US">0</span>。<span lang="EN-US"><o:p></o:p></span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1 1<br/>
5 5<br/>
1 3 3 3<br/>
6 2 8 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p><a href="/JudgeOnline/upload/201604/2541.rar">数据如下：JudgeOnline/upload/201604/2541.rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

