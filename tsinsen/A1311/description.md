<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont">　　﻿</div>
# 问题描述

<div class="pdcont">　　在平面直角坐标系中有n条互不相交(没有公共点)且所在直线不会经过(0,0)的线段。有一个人站在(0,0)，他的视野是360度的。但是他在某一个方向上的视野会被该方向上碰到的第一条线段所阻挡，问他能看到的区域面积有多大（数据保证是有限面积）。如下图（样例），可以看到的面积就是11。<br/>
<img width="190" height="181" src="source/tsinsen/A1311/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZzNoUm5GeTI=.do"/><br/>
<br/>
　　为了加大难度，他想知道，在删除一条线段的情况下能看到最大多大的面积（不保证是有限面积）。<br/>
　　进一步，他还想知道，在删除两条线段的情况下能看到最大多大的面积（不保证是有限面积）。</div>
# 输入格式

<div class="pdcont">　　第一行一个整数n表示线段条数。<br/>
　　接下来n行，每行四个整数x1,y1,x2,y2表示一条线段两个端点的坐标。</div>
# 输出格式

<div class="pdcont">　　第一行一个保留两位小数的实数，表示可见区域的面积。<br/>
　　第二行两种可能，如果删除一条线段以后能使得看到的区域有无限大输出”infinite”，否则输出一个保留两位小数的实数，表示这种情况下能看到的最大面积。<br/>
　　第三行两种可能，如果删除两条线段以后能使得看到的区域有无限大输出”infinite”，否则输出一个保留两位小数的实数，表示这种情况下能看到的最大面积。</div>
# 样例输入

<div class="pddata">6<br/>
-1 -1 0 -1<br/>
0 -2 1 -1<br/>
-1 1 0 2<br/>
0 1 1 1<br/>
2 -2 2 2<br/>
-2 -2 -2 2</div>
# 样例输出

<div class="pddata">11.00<br/>
infinite<br/>
infinite</div>
# 数据规模和约定

<div class="pdcont">　　对于所有数据<br/>
　　1&lt;=n&lt;=50000<br/>
　　坐标的绝对值&lt;=10<sup>3</sup><br/>
<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area1.in<br/>
</td><td valign="top" colspan="2" style="border:solid 1.0pt">4<br/>
-1 2 4 2<br/>
2 1 2 -4<br/>
1 -2 -4 -2<br/>
-2 -1 -2 4<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area2.in<br/>
</td><td valign="top" colspan="2" style="border:solid 1.0pt">8<br/>
-1 2 4 2<br/>
2 1 2 -4<br/>
1 -2 -4 -2<br/>
-2 -1 -2 4<br/>
-3 6 12 6<br/>
6 3 6 -12<br/>
3 -6 -12 -6<br/>
-6 -3 -6 12<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area3.in<br/>
</td><td valign="top" colspan="2" style="border:solid 1.0pt">12<br/>
-1 2 4 2<br/>
2 1 2 -4<br/>
1 -2 -4 -2<br/>
-2 -1 -2 4<br/>
-3 6 12 6<br/>
6 3 6 -12<br/>
3 -6 -12 -6<br/>
-6 -3 -6 12<br/>
-9 18 36 18<br/>
18 9 18 -36<br/>
9 -18 -36 -18<br/>
-18 -9 -18 36<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area4.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=10，坐标的绝对值&lt;=10。<br/>
</td><td valign="top" style="border:solid 1.0pt">删除某条线段后可看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area5.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=1000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除某条线段后可看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area6.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=1000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除某条线段后可看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area7.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除某条线段后可看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area8.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除某条线段后可看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area9.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除某条线段后可看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area10.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除某条线段后可看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area11.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=200<br/>
</td><td valign="top" style="border:solid 1.0pt">删除两条线段后能看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area12.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=1000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除两条线段后能看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area13.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=1000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除两条线段后能看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area14.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除两条线段后能看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area15.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt">删除两条线段后能看到无限区域<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area16.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area17.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=300<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area18.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area19.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">area20.in<br/>
</td><td valign="top" style="border:solid 1.0pt">n&lt;=50000<br/>
</td><td valign="top" style="border:solid 1.0pt"><br/>
</td></tr></tbody></table></div>

</div>