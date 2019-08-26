
# Description

<div class="content"><div style="text-indent: 21.25pt"><span style="font-size: medium">多边形之战是一个双人游戏。游戏在一个有n个顶点的凸多边形上进行，这个凸多边形的n-3条对角线将多边形分成n-2个三角形，这n-3条对角线在多边形的顶点相交。三角形中的一个被染成黑色，其余是白色。双方轮流进行游戏，当轮到一方时，他必须沿着画好的对角线，从多边形上切下一个三角形。切下黑色三角形的一方获胜。</span></div>
<div style="text-indent: 21.25pt"><span style="font-size: medium">注：如果连接一个多边形中任意两点的线段都完全包含于这个多边形，则称这个多边形为凸多边形。</span></div>
<div style="margin: 13pt 0cm"><span style="font-size: medium"><b><span style="line-height: 173%">求解任务：</span></b></span></div>
<div><span style="font-size: medium">请设计一个程序：</span></div>
<div><span style="font-size: medium">       ·读入对一个多边形的描述。</span></div>
<div style="text-indent: 21.25pt"><span style="font-size: medium">·确定先走的一方是否能够获胜。</span></div>
<div style="text-indent: 21.25pt"><span style="font-size: medium">·将结果输出。</span></div></div>

# Input

<div class="content"><div style="margin: 13pt 0cm"><span style="font-size: medium">第一行是一个整数， 4 &lt;= n &lt;= 50000。表示多边形的顶点数，多边形的顶点从0到n-1顺时针标号。接着的n-2行描述组成多边形的三角形。第i+1行， 1 &lt;= i &lt;= n-2，有三个空格分隔的非负整数a、 b、 c，它们是第i个三角形的顶点编号。第一个给出的三角形是黑色的。</span></div></div>

# Output

<div class="content"><div style="text-indent: 21.25pt"><span style="font-size: medium">唯一一行应包含一个单词：</span></div>
<div style="text-indent: 21.25pt"><span style="font-size: medium">TAK（波兰文“是”)，表示先走的一方有必胜策略，或者</span></div>
<div style="text-indent: 21.25pt"><span style="font-size: medium">NIE（波兰文“否”），表示先走的一方没有必胜策略。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
0 1 2<br/>
2 4 3<br/>
4 2 0<br/>
0 5 4<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

