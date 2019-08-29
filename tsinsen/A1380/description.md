<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont"><b>【问题描述】</b><br/>
　　二维平面被划分成若干个简单多边形，每个简单多边形必与至少一个多边形共边，且多边形两两之间公共面积为0。所有多边形的并为一个简单多边形（即不存在图1所示情况）。<br/>
　　区域定义为：一个多边形，或者多边形的并关于平面的补集。<br/>
　　如图2，黑框表示三个简单多边形的边界，该平面共有4个区域。<br/>
　　<img width="150" height="132" src="source/tsinsen/A1380/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9YWFuUmpiamQ=.do"/>   <img width="150" height="132" src="source/tsinsen/A1380/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9dFRtTDhCRzI=.do"/>   <img width="150" height="132" src="source/tsinsen/A1380/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NjI5NEhIZEY=.do"/>  ·<br/>
　　简单多边形的每条边&lt;p, q&gt;有两个方向(p-&gt;q和q-&gt;p)，每个方向有一个激活费用V，表示激活这条边的该方向要花费代价V。V=0则该边的该方向不可被激活。如图3，激活了该方向后，就能无数次从向量&lt;p, q&gt;的逆时针方向走到顺时针方向，但不能从向量&lt;p, q&gt;的顺时针方向走到逆时针方向，即从区域A能走到区域B，但不能从区域B走到区域A。<br/>
　　Wayne希望你能帮他找到一个区域a，使得任取一个区域b，都能从a出发到达b。求在此区域a下的最小总激活费用。保证存在这个区域。<br/>
<br/>
<b>【输入格式】</b><br/>
　　第一行两个整数n和m，表示点与线段的数目。<br/>
　　接下来n行，每行两个整数x和y，表示第i个点的坐标，点从1到n编号。<br/>
　　接下来m行，每行四个整数p,q,V1和V2，表示存在一条从第p个点连向第q个点的线段，激活p-&gt;q这个方向的费用为V1，另一个方向费用为V2。<br/>
　　保证若两条线段相交，则交点是它们的公共端点。<br/>
<br/>
<b>【输出格式】</b><br/>
　　输出一行一个正整数，表示最小总激活费用。</div>
# 样例输入

<div class="pddata">4 5<br/>
0 0<br/>
1 0<br/>
0 1<br/>
1 1<br/>
1 2 0 0<br/>
1 3 0 3<br/>
2 3 1 0<br/>
2 4 2 0<br/>
4 3 0 0</div>
# 样例输出

<div class="pddata">3<br/>
<br/>
<b>【样例解释】</b><br/>
<b><img width="200" height="185" src="source/tsinsen/A1380/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9SDRtOTVIRUc=.do"/><img width="200" height="156" src="source/tsinsen/A1380/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9YlFyYjNMcW0=.do"/>·</b><br/>
样例如左图，等价于右图所示有向图。则激活1-&gt;2与2-&gt;3后，能从1出发到达2和3。所以最小总激活费用为3。<br/>
<br/>
<b>【数据规模】</b><br/>
对于60%的数据，边的两个方向上激活费用相等；其中1/2的数据，多边形由边长为1的正方形组成，且所有多边形的并为矩形，如下图所示：<br/>
<img width="200" height="176" src="source/tsinsen/A1380/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9UjRnbUxyRFQ=.do"/>·<br/>
另外20%的数据，区域数≤18；<br/>
另外10%的数据，区域数≤150；<br/>
对于100%的数据，n≤3000，区域数不超过1000，点坐标绝对值不超过1W，每条边激活费用不超过100。</div>

</div>