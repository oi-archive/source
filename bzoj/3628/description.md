
# Description

<div class="content"><div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">在游戏天天酷跑中，最爽的应该是超级奖励模式了吧，没有一切障碍，可以尽情的吃金币，现在请你控制游戏角色来获得尽可能多的分数。</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium">游戏界面离散为一个长度为1~n，高度为1~m（初始点为（0，1））的矩阵图。每个格子上都有收益（-1~1000），-1表示该点不能通过。游戏角色从起点一路奔跑向终点，中途可以跳跃来获得更高的分数，在空中还能进行连跳。游戏开始前你可以设定跳跃的高度，以及能连跳的次数，初始跳跃高度为1，连跳数为1（最多为5），升级跳跃高度和连跳都需要一定的花费。跳跃高度设定完后游戏角色每次跳跃高度都将固定，连跳必须在下落过程中可以使用。所有操作都将在整点上完成，需要保证设定完的跳跃高度及连跳数，无法跳出游戏高度上限。</span></div>
<div style="margin: 0cm 0cm 10pt"><span style="font-size: medium"><img alt="" width="464" height="203" src="/source/bzoj/3628/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNi8xMS5qcGc=.jpg"/></span></div>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><font size="3"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">以下是连跳数为</span><span lang="EN-US">2</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">连跳，跳跃高度为</span><span lang="EN-US">2</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">的跳跃方案：</span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><font size="3"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma"><img alt="" width="611" height="466" src="/source/bzoj/3628/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNi8yMi5qcGc=.jpg"/></span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span style="font-size: medium"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">第一行四个整数</span><span lang="EN-US">n</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">m</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">cost1</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">cost2</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">。</span><span lang="EN-US">n</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">m</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">如题意所示，</span><span lang="EN-US">cost1</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">cost2</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">分别表示每升一级跳跃高度，连跳数所需的花费。</span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span style="font-size: medium"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">接下来</span><span lang="EN-US">m</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">行，每行</span><span lang="EN-US">n</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">个数。第</span><span lang="EN-US">i</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">行第</span><span lang="EN-US">j</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">个数表示地图中高度为</span><span lang="EN-US">i</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，长度在第</span><span lang="EN-US">j</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">列处的收益。</span></font></span></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 10pt"> </p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span style="font-size: medium"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">如果无法跑出终点线，就输出</span><span lang="EN-US">“mission failed”</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，否则输出一行三个数，分别表示最大收益；及最大收益时，最小的连跳数；最大收益，最小连跳数时，最小的跳跃高度。</span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span style="font-size: medium"><span lang="EN-US"><o:p></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 4 6 10<br/>
<br/>
9 4 7 7 4 3 2<br/>
<br/>
18 8 9 4 15 12 4<br/>
<br/>
19 2 4 7 10 18 12<br/>
<br/>
8 1 13 14 16 0 14<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">67 1 2<br/>
<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">提示</span></p><br/>
<p><span style="font-size: medium">20%数据满足 m=2， n&lt;=100000;</span></p><br/>
<p><span style="font-size: medium"> </span></p><br/>
<p><span style="font-size: medium">另有80%数据 n&lt;=10000，2&lt;m&lt;=20，其中20%数据 2&lt;n&lt;=10，m&lt;=10;<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

