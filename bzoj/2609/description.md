
# Description

<div class="content"><p><span lang="EN-US"><font face="Verdana">Bytel </font></span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">公司开始生产一种串</span><span lang="EN-US"><font face="Verdana">-</font></span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">并联电路，每个这样的电路包含很多相连的电子单元以及两个电源，一个串</span><span lang="EN-US"><font face="Verdana">-</font></span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">并联电路可能有以下组成</span><span lang="EN-US"><font face="Verdana">: </font></span></p>
<p><span lang="EN-US"><font face="Verdana"><img height="457" width="487" alt="" src="/source/bzoj/2609/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMy8xKDMpLmpwZw==.jpg"/></font></span></p>
<p><span lang="EN-US"><font face="Verdana">
</font></span></p><p><font face="Verdana"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">这些电路都将组装在一个双面的电路板上。现在的问题就是要确定哪些电路印在正面和哪些印在反面。因为一些技术原因电路应该尽量多的印在反面，但是要求每个单元至少要有一条连接的线路印在正面。求怎样规划使得印在正面的线路最少。</span></span></font></p><font face="Verdana">
</font><p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">电路的定义由以下的递归方式进行</span><span lang="EN-US" style="font-family: Verdana">: </span></span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana"><o:p></o:p></span></p>
<ul type="disc">
    <li class="MsoNormal" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; tab-stops: list 36.0pt; mso-list: l0 level1 lfo1"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">如果第一行有一个大写字母</span><tt><span lang="EN-US"><font face="宋体">S</font></span></tt><span lang="EN-US" style="font-family: Verdana"> </span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">和一个整数</span><i><span lang="EN-US" style="font-family: Verdana">n</span></i><span lang="EN-US" style="font-family: Verdana"> (2 &lt;= <i>n</i> &lt;= 10000) </span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">，那么这个电路将由</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-family: Verdana">n</span></i><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">个小的串</span><span lang="EN-US" style="font-family: Verdana">-</span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">并联电路串联在一起构成，这些小网络紧接着在下面的行进行描述</span><span lang="EN-US" style="font-family: Verdana">, </span></span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana"><o:p></o:p></span></li>
    <li class="MsoNormal" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; tab-stops: list 36.0pt; mso-list: l0 level1 lfo1"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">如果第一行有一个大写字母</span><tt><span lang="EN-US"><font face="宋体">R</font></span></tt><span lang="EN-US" style="font-family: Verdana"> </span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">和一个整数</span><i><span lang="EN-US" style="font-family: Verdana">n</span></i><span lang="EN-US" style="font-family: Verdana"> (2 &lt;= <i>n</i> &lt;= 10000) </span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">，那么这个电路将由</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-family: Verdana">n</span></i><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">个小的串</span><span lang="EN-US" style="font-family: Verdana">-</span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">并联电路并联在一起构成，这些小网络紧接着在下面的行进行描述</span><span lang="EN-US" style="font-family: Verdana">, </span></span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana"><o:p></o:p></span></li>
    <li class="MsoNormal" style="margin: 0cm 0cm 0pt; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; tab-stops: list 36.0pt; mso-list: l0 level1 lfo1"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">如果一行只有一个大写字母</span><tt><span lang="EN-US"><font face="宋体">X</font></span></tt><span lang="EN-US" style="font-family: Verdana"> </span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">那么这个电路仅有一个电子单元</span><span lang="EN-US" style="font-family: Verdana">. </span></span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana"><o:p></o:p></span></li>
</ul>
<p style="margin-left: 36pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">大写字母</span><tt><span lang="EN-US"><font face="宋体">X</font></span></tt><span lang="EN-US"><font face="Verdana"> </font></span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">的出现总数不会超过</span><span lang="EN-US"><font face="Verdana">10000000, </font></span><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">递归的层数最大不超过</span><span lang="EN-US"><font face="Verdana">500.</font></span></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt 36pt; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Verdana; mso-hansi-font-family: Verdana">输出仅一个数，表示最少有多少线路印在正面</span><span lang="EN-US" style="font-family: Verdana">. </span></span><span lang="EN-US" style="font-size: 9pt; font-family: Verdana"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">R 3<br/>
S 2<br/>
X<br/>
R 2<br/>
S 2<br/>
X<br/>
X<br/>
S 2<br/>
X<br/>
X<br/>
S 3<br/>
X<br/>
X<br/>
X<br/>
R 2<br/>
X<br/>
X<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
8<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

