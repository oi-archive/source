<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　二维平面上的山脉由一系列顶点确定：(x1,y1),(x2,y2)...(xn,yn)。相邻的两个顶点之间由线段相连（保证xi严格递增），这样就构成了一座连绵的山脉，每个点的y值代表了该点的高度。如下图所示：<br/>
<img src="source/tsinsen/A1482/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9cmYyZ0JhTjY=.do" width="400" height="171"/><br/>
　　。<br/>
　　我们定义山脉的内部为顶点之间的折线与x轴的所夹部分（不包括顶点之间的折线）。如果顶点A与顶点B之间的连线段没有穿过山脉的内部，则我们称顶点A能看见顶点B（或B能看见A）。<br/>
<br/>
　　现在pty从某个顶点出发，想要登到山脉的顶峰（最高点），他只能在顶点之间的折线上行走。经过思考，他将采取如下的一种登山方式：<br/>
　　1、站在出发点，向左右看去，如果此时能够看到的最高山峰在左侧，则向左侧走去，否则向右侧走去。<br/>
　　2、在行走的同时，pty仍然观察着此时左右的最高山峰，一旦发现一座比之前看到的都要高的山峰，他将向此时的最高峰走去。<br/>
　　3、如果存在某个时刻，pty所站立的位置比左右能看到的最高峰都要高，则他到达了山脉的顶峰，此时他的爬山过程结束。<br/>
<br/>
　　pty想知道，采取如上的策略，从每个顶点出发，到达最高点的路程分别是多少？（平面中两点的距离等于它们之间连线段的长度）</div>
# 输入格式

<div class="pdcont">　　第一行一个整数n，表示山脉顶点个数。<br/>
　　接下来n行，第i行两个整数xi,yi，表示第i个顶点的坐标。<br/>
　　保证xi严格递增，yi互不相同（y1,yn除外），xi,yi都为非负整数。保证y1,yn的值为0。</div>
# 输出格式

<div class="pdcont">　　输出共n行：每行一个实数<br/>
　　第i行的实数表示从第i个顶点出发，到达最高点的路程。保留两位小数。</div>
# 样例输入

<div class="pddata">6<br/>
0 0<br/>
1 6<br/>
2 4<br/>
3 1<br/>
5 5<br/>
6 0</div>
# 样例输出

<div class="pddata">6.08<br/>
0.00<br/>
2.24<br/>
6.52<br/>
9.87<br/>
14.97</div>
# 样例说明

<div class="pdcont"><img src="source/tsinsen/A1482/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9QWVCbjZSN1E=.do"/><br/>
　　。<br/>
<br/>
　　路线说明：<br/>
　　A点出发：A-&gt;B<br/>
　　B点出发：B<br/>
　　C点出发：C-&gt;B<br/>
　　D点出发：D-&gt;G-&gt;D-&gt;C-&gt;B<br/>
　　E点出发：E-&gt;D-&gt;C-&gt;B<br/>
　　F点出发：F-&gt;E-&gt;D-&gt;C-&gt;B<br/>
　　从D点出发时，看到的最高点是E，当步行至G点时，发现更高点B，转向后一直步行向B点。从其它点出发后都不需要转向。</div>
# 数据规模和约定

<div class="pdcont">　　所有的数据满足xi,yi&lt;=100000。<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试点编号</td><td style="border:solid 1.0pt">限制条件</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1-4</td><td style="border:solid 1.0pt">n&lt;=20</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5-8</td><td style="border:solid 1.0pt">n&lt;=70</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9-10</td><td style="border:solid 1.0pt">满足n&lt;=100000且每个顶点都能直接看到最高点</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">11-14</td><td style="border:solid 1.0pt">n&lt;=30000</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">15-20</td><td style="border:solid 1.0pt">n&lt;=100000</td></tr></tbody></table></div>

</div>