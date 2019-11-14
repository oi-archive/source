<div id="pcont1" style="margin-top:20px; display:block;">

# 试题来源

<div class="pdcont">　　本题为一道经典模拟题，来自CTSC2002。本题的目的为考查和锻炼各位集训队员的编程能力和细心的习惯。</div>
# 问题描述

<div class="pdcont">　　最近，有一些繁殖力很强的老鼠在下水道非常猖獗，灭鼠特工队正在计划消灭这些老鼠。下水道只有东西方向和南北方向的管道，如图所示。<br/>
<br/>
<img width="560" height="231" src="source/tsinsen/A1283/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ck5GdHFxRkc=.do"/><br/>
　　灭鼠特工队的队员拥有强大的武器。他们将在某些时刻t在某些位置(x,y)放置武器。他们所使用的武器包括：<br/>
　　1.        强力炸弹：它的攻击范围限定在管道内部，是沿竖直和水平方向，离(x,y)的距离不超过L的区域，但是不能穿透下水道壁。它将在放置之后立刻爆炸，且攻击范围内的老鼠将被全部炸死。<br/>
　　2.        神秘射线：它的攻击范围是以(x,y)为圆心，半径为R的圆，而且可以穿透下水道壁。射线在时刻t施放后，将使攻击范围内的所有老鼠立刻陷入昏迷状态，失去知觉，停止一切生理活动，待到第t+3时刻才能恢复（保持失去知觉前的朝向）。如果在昏迷状态中再次受到射线攻击，那么它将再推迟3个时刻恢复。例如，若老鼠在时刻t和时刻t+1个受到一次射线的攻击，则它要昏迷到第t+3+3时刻才能恢复知觉。恢复知觉以后，老鼠将继续以前的生理活动。<br/>
　　3.        定时炸弹：它的攻击范围仅包括(x,y)。它在时刻t放置后，将在第t+3时刻爆炸，爆炸时处在(x,y)点的老鼠将全部被炸死。<br/>
　　4.        生物炸弹：它的攻击范围仅包括(x,y)。它将在放置之后立刻爆炸，使处在(x,y)点的所有老鼠的性别改变（无论大小，雌变成雄，雄变成雌），但不影响老鼠的正常生理活动。<br/>
　　虽然特工队的实力很强，但是老鼠的实力也不容忽视。<br/>
　　我们定义，相邻两个时刻之间是一个时间单位。从t=0时刻开始，每只老鼠就从初始位置向某一初始方向运动。只要前方有管道，如上图中沿方向N到达点A，老鼠就会一直向前走，运动速度为1。否则，如果只有左边或者只有右边有管道，如上图中沿方向E到达点B时，再不能沿原方向继续前进，它就会花费一个时间单位朝该方向原地转动90度，即它将改变方向朝向S。如果它左边和右边都有管道，如上图中沿方向W到达点C，老鼠会回忆这是第几次处于这种情况。如果是第奇数次遇到，它会向左转，第偶数次就向右转。如果它处于一条死路的尽头，如上图中沿方向W到达点D，那么它会花费两个时间单位连续向右转两次，即它将改变方向朝向E。<br/>
　　如果在t时刻某点恰好只有两只老鼠，一只为成年雄老鼠，一只为成年雌老鼠，则它们将会因为进行繁殖而在该点停留两个单位时间，t+2时刻会在该点对每个有管道的方向生出一只朝着该方向的小老鼠，南北方向为雄小老鼠，东西方向为雌小老鼠。如上图中的C点，t时刻恰好只有两只老鼠，它们都已成年且性别相异，那么在第t+2时刻就会在该点生出三只小老鼠，它们分别朝向N、S、E，性别分别是雄性、雄性、雌性。小老鼠一出生就立刻开始移动，而成年老鼠需要再休息一个时间单位，即在t+3时刻继续活动（两只老鼠都保持生育前的朝向）。小老鼠需要成长5个时间单位才会长成为成年老鼠。<br/>
　　特工队现在制定了一套灭鼠计划，其中包括在下水管道放置武器的位置、时间和类型。你需要帮他们计算灭鼠行动的效果，如果在该计划实施的过程中，老鼠的数量超过了某个限定值，就会爆发鼠疫。<br/>
<br/>
　　【输入文件】<b></b><br/>
　　输入的第一行为4个整数L R m n(0&lt;=L,R&lt;=10,1&lt;=m,n&lt;=50)，其中L代表强力炸弹的有效攻击距离，R代表神秘射线的作用半径，m和n代表下水道平面图的规模。x坐标的范围为[1,m], y坐标的范围为[1,n]。<br/>
　　从第2行到第m+1行为下水道结构图。我们用方向数1代表N(北)，用方向数2代表E(东)，用方向数4代表S(南)，用方向数8代表W(西)。第i+1行的第j个数字c<sub>i,j</sub>代表点(i,j)处有管道连接的所有方向数之和，如上图中的点B的方向数之和为12。<br/>
　　第m+2行为一个整数K（1&lt;=K&lt;=50），代表时刻0时老鼠的个数（此时老鼠都是成年的）。<br/>
　　第m+3行到第m+K+2行每行描述一只老鼠，包括该老鼠的初始坐标(x,y) (1&lt;=x&lt;=m, 1&lt;=y&lt;=n)，朝向（’E’,’S’,’W’,’N’）以及性别（’X’=雄，’Y’=雌）。输入保证每个老鼠都在水管内。<br/>
　　第m+K+3行为两个整数P，Limit(1&lt;=P, Limit&lt;=100)，分别表示特工队准备使用的武器个数以及控制鼠疫发生的老鼠数量的极限。<br/>
　　第m+K+4行到第m+K+P+3行每行描述一个武器，包括该武器的类型(1-强力炸弹，2-神秘射线，3-定时炸弹，4-生物炸弹)，放置的时刻t(t&gt;=1)，放置的坐标(x,y) (1&lt;=x&lt;=m, 1&lt;=y&lt;=n)，输入保证武器放置在管道内。武器按照放置的时间不降序排列。<br/>
　　<b>    </b>最后一行包含一个整数Time(1&lt;=Time&lt;=1000)，表示模拟的结束时刻。Time保证比所有武器的放置时刻大。<br/>
<br/>
　　【输出文件】<b></b><br/>
　　输出包含一个整数。如果爆发了鼠疫，该整数为-1，否则该整数为时刻Time的老鼠数目。<br/>
<b> </b></div>
# 样例输入

<div class="pddata">1 1 3 3<br/>
6 14 12<br/>
7 15 13<br/>
3 11 9<br/>
3<br/>
1 3 W X<br/>
1 2 W X<br/>
3 3 S X<br/>
3 100<br/>
1 1 2 2<br/>
3 1 3 1<br/>
2 2 3 2<br/>
10</div>
# 样例输出

<div class="pddata">1<br/>
【样例1说明】<b></b><br/>
各个时刻每只老鼠的情况如下表：<br/>
<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td rowspan="2" style="border:solid 1.0pt">时刻<br/>
</td><td colspan="3" valign="top" style="border:solid 1.0pt">老鼠1<br/>
</td><td colspan="3" valign="top" style="border:solid 1.0pt">老鼠2<br/>
</td><td colspan="3" valign="top" style="border:solid 1.0pt">老鼠3<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">坐标<br/>
</td><td valign="top" style="border:solid 1.0pt">朝向<br/>
</td><td valign="top" style="border:solid 1.0pt">状态<br/>
</td><td valign="top" style="border:solid 1.0pt">坐标<br/>
</td><td valign="top" style="border:solid 1.0pt">朝向<br/>
</td><td valign="top" style="border:solid 1.0pt">状态<br/>
</td><td valign="top" style="border:solid 1.0pt">坐标<br/>
</td><td valign="top" style="border:solid 1.0pt">朝向<br/>
</td><td valign="top" style="border:solid 1.0pt">状态<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">(1,3)<br/>
</td><td valign="top" style="border:solid 1.0pt">W<br/>
</td><td valign="top" style="border:solid 1.0pt">正常<br/>
</td><td valign="top" style="border:solid 1.0pt">(1,2)<br/>
</td><td valign="top" style="border:solid 1.0pt">W<br/>
</td><td valign="top" style="border:solid 1.0pt">正常<br/>
</td><td valign="top" style="border:solid 1.0pt">(3,3)<br/>
</td><td valign="top" style="border:solid 1.0pt">S<br/>
</td><td valign="top" style="border:solid 1.0pt">正常<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">死亡<br/>
</td><td valign="top" style="border:solid 1.0pt">(1,1)<br/>
</td><td valign="top" style="border:solid 1.0pt">W<br/>
</td><td valign="top" style="border:solid 1.0pt">正常<br/>
</td><td valign="top" style="border:solid 1.0pt">(3,3)<br/>
</td><td valign="top" style="border:solid 1.0pt">W<br/>
</td><td valign="top" style="border:solid 1.0pt">正常<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">死亡<br/>
</td><td valign="top" style="border:solid 1.0pt">(1,1)<br/>
</td><td valign="top" style="border:solid 1.0pt">S<br/>
</td><td valign="top" style="border:solid 1.0pt">正常<br/>
</td><td valign="top" style="border:solid 1.0pt">(3,2)<br/>
</td><td valign="top" style="border:solid 1.0pt">W<br/>
</td><td valign="top" style="border:solid 1.0pt">昏迷<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">死亡<br/>
</td><td valign="top" style="border:solid 1.0pt">(2,1)<br/>
</td><td valign="top" style="border:solid 1.0pt">S<br/>
</td><td valign="top" style="border:solid 1.0pt">正常<br/>
</td><td valign="top" style="border:solid 1.0pt">(3,2)<br/>
</td><td valign="top" style="border:solid 1.0pt">W<br/>
</td><td valign="top" style="border:solid 1.0pt">昏迷<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">死亡<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">死亡<br/>
</td><td valign="top" style="border:solid 1.0pt">(3,2)<br/>
</td><td valign="top" style="border:solid 1.0pt">W<br/>
</td><td valign="top" style="border:solid 1.0pt">昏迷<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">死亡<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">N/A<br/>
</td><td valign="top" style="border:solid 1.0pt">死亡<br/>
</td><td valign="top" style="border:solid 1.0pt">(3,2)<br/>
</td><td valign="top" style="border:solid 1.0pt">W<br/>
</td><td valign="top" style="border:solid 1.0pt">正常<br/>
</td></tr></tbody></table><br/>
以后老鼠数目不再变化，因此时刻10仍然只有1只老鼠。</div>
# 样例输入

<div class="pddata">2 3 5 6<br/>
6 10 14 10 14 12<br/>
5 0 5 0 3 13<br/>
3 10 9 0 0 5<br/>
0 0 0 0 0 5<br/>
0 0 0 0 2 9<br/>
4<br/>
3 1 N X<br/>
3 2 E Y<br/>
2 6 S Y<br/>
1 5 W X<br/>
3 80<br/>
1 1 1 4<br/>
1 21 2 6<br/>
1 41 5 6<br/>
80</div>
# 样例输出

<div class="pddata">73</div>

</div>