<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在一个叫做Aalam-Aara的城镇，以前那里没有丑恶、没有犯罪。但是随着时间推移，罪恶的念头逐渐蔓延至这些曾经正直的人们心中。为了解决这个问题，一些老者发现，只要那些已经变坏的人们与正直的人们隔离开来，犯罪就会停止。所以，他们尝试建造一个监狱来关押那些坏人们。为了保证罪犯们不会逃脱，还需要建造一个瞭望塔，以便于监视这些罪犯。<br/>
　　由于Aalam-Aara镇的人们不是很富裕，一个来自其他城镇的富商答应卖给他们一小块地皮。这块地皮的一条直线上已经造好了一段围墙AB，其上有一些点可以作为瞭望塔的建造地。只能建造一座瞭望塔，所以要求通过这座瞭望塔能够看见这块地皮的每一个角落。我们说某个点是看得见的，当且仅当瞭望塔与这个点的连线段不穿过地皮的边界。如图1，若选择点B建造瞭望塔，X、Y、C、A点就是看得见的，而E、D两点看不见。你的任务是告诉他们一共有多少个点是满足要求的。<br/>
<img width="339" height="322" src="source/tsinsen/A1418/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RE1STkd5TkY=.do"/><br/>
　　图 1<br/>
<br/>
<img width="329" height="208" src="source/tsinsen/A1418/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9Zk5EODVlVG4=.do"/><br/>
　　图 2<br/>
　　假定地皮的形状是一个多边形，建立直角坐标系满足AB平行于x轴。AB边上的所有整点是可以建造瞭望塔的点。如图2，AB边上的5个整点(4,8)，(5,8)，(6,8)，(7,8)，(8,8)可以建造瞭望塔。数据保证多边形任意三个相邻的顶点不共线，所有顶点都在直线AB的同侧，且该多边形不会有自交。</div>
# 输入格式

<div class="pdcont">　　第一行：一个整数n，表示多边形顶点数（3≤n≤1000）。<br/>
　　接下来n行每行两个整数<i>x<sub>i</sub></i>，<i>y<sub>i</sub></i>表示一个顶点的坐标（0 ≤ <i>x<sub>i</sub></i>, <i>y<sub>i</sub></i> ≤ 10<sup>6</sup>）。顶点坐标按顺时针顺序给出。<br/>
　　AB的两个端点为开始的两个顶点，即(<i>x</i><sub>1</sub>, <i>y</i><sub>1</sub>)和(<i>x</i><sub>2</sub>, <i>y</i><sub>2</sub>)。</div>
# 输出格式

<div class="pdcont">　　一行一个整数，为AB边上满足要求的整点个数。<br/>
<b><br/>
</b><br/>
<b>样例输入1</b><br/>
　　5<br/>
　　4 8<br/>
　　8 8<br/>
　　9 4<br/>
　　4 0<br/>
　　0 4<br/>
<b>样例输出1</b><br/>
　　5<br/>
<b>样例输入2</b><br/>
　　5<br/>
　　4 8<br/>
　　5 8<br/>
　　5 4<br/>
　　7 4<br/>
　　2 2<br/>
<b>样例输出2</b><br/>
　　0<br/>
<b>样例解释</b><br/>
　　样例1为图2的情况，AB边上的五个整点都满足要求，答案是5。<br/>
　　样例2，设点依次为ABCDE，则CD和DE两边不能全部被看到，答案是0。</div>

</div>