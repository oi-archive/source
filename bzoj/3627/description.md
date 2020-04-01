
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma"><font size="3" face="Tahoma">相信大家都用过地图上的路径规划功能，只要输入起点终点就能找出一条最优路线。现在告诉你一张地图的信息，请你找出最优路径（即最短路径）。考虑到实际情况，一辆车加满油能开的时间有限，所以在地图上增加了几个加油站。</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><font size="3"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">地图由点和双向边构成，每个点代表一个路口，也有可能是加油站或起点终点。有些路口还装有红绿灯。由于经过太多的红绿灯会让人感到不爽，所以请求在经过不超过</span><span lang="EN-US">k</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">个红绿灯的情况下，最少平均花费多少时间能从起点到终点。保证起点终点和加油站没有红绿灯。</span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma"><font size="3" face="Tahoma">（题目不考虑最坏情况下能否加到油，只考虑平均花费时间的前提下，车能否到达加油站加油）。</font></span></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 10pt"><font size="3"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">第一行输入</span><span lang="EN-US">5</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">个整数</span><span lang="EN-US">n</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">m</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">k</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">limit</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">cost</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，表示有</span><span lang="EN-US">n</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">个点</span><span lang="EN-US">m</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">条边，车能开</span><span lang="EN-US">limit</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">长的时间，及加油所花时间</span><span lang="EN-US">cost</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">。</span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><font size="3"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">接下来</span><span lang="EN-US">n</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">行输入每个点信息，包括点的名称（带</span><span lang="EN-US">“gas”</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">的为加油站，</span><span lang="EN-US">“start”</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">为起点，</span><span lang="EN-US">“end”</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">为终点），及该点是否有红绿灯，（</span><span lang="EN-US">a</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，</span><span lang="EN-US">b</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">表示）（若为</span><span lang="EN-US">a=0</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">则表示没有，</span><span lang="EN-US">a</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">表示红灯长，</span><span lang="EN-US">b</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">表示绿灯长）。</span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><font size="3"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">接下来</span><span lang="EN-US">m</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">行输入每条边信息，包括边的起点，终点，边的名称，通过该边所花时长。</span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><font size="3"><font face="Tahoma"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">保证点和边名的长度不大于</span><span lang="EN-US">20</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">，只有大小写字母，数字及</span><span lang="EN-US">‘_’</span><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">组成。</span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span lang="EN-US"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span style="font-family: 微软雅黑; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma"><font size="3" face="Tahoma">一行输出最少平均花费时长。</font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 10pt"><span lang="EN-US"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 8 1 100 10<br/>
start 0 0<br/>
azhan 10 10<br/>
xxgasxx 0 5<br/>
bpoint 20 5<br/>
end 0 100<br/>
start azhan sdf 30<br/>
azhan xxgasxx ewfg 20<br/>
start end r3tg 200<br/>
end azhan 1xq2 70<br/>
azhan bpoint gg 10<br/>
xxgasxx bpoint kk 30<br/>
bpoint end dsg 40<br/>
xxgasxx end t_s 100<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">162.500<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
共14组数据：</span></p><br/>
<p><span style="font-size: medium"> </span></p><br/>
<p><span style="font-size: medium">其中3组数据，满足n&lt;10，m&lt;20，k&lt;5</span></p><br/>
<p><span style="font-size: medium"> </span></p><br/>
<p><span style="font-size: medium">另有3组没有红绿灯</span></p><br/>
<p><span style="font-size: medium"> </span></p><br/>
<p><span style="font-size: medium">所有数据满足n&lt;=10000，m&lt;=20000，k&lt;=10，加油站&lt;=50</span></p><br/>
<p><span style="font-size: medium"> </span></p><br/>
<p><span style="font-size: medium">答案保留3位小数</span></p><br/>
<p><span style="font-size: medium"> <br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

