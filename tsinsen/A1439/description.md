<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定平面上的n个点。你需要去删掉恰好k个点(k&lt;n)，使得剩下的n-k个点所构成的集合的直径尽量小。一个点集的直径是指集合中最远点对的距离。只含一个点的集合的直径等于0。</div>
# 输入格式

<div class="pdcont">　　第一行包含一对整数n,k (2≤n≤1000, 1≤k≤30, k&lt;n)——对应平面上点的个数和需要删掉的点数。<br/>
　　接下来n行描述了这些点，一个点一行。每个描述包括一对整数，xi,yi(0≤xi,yi≤32000)——第i个点的坐标。给出的点可以重合。</div>
# 输出格式

<div class="pdcont">　　输出k个不同的用空格隔开的整数——删除的点的标号。<br/>
　　输入中给出的点是有序的，标号为1到n。你可以用任意顺序输出这些标号。如果有多组解，输出任意一组。</div>
# 样例输入

<div class="pddata">样例1<br/>
5 2<br/>
1 2<br/>
0 0<br/>
2 2<br/>
1 1<br/>
3 3<br/>
样例2<br/>
4 1<br/>
0 0<br/>
0 0<br/>
1 1<br/>
1 1</div>
# 样例输出

<div class="pddata">样例1<br/>
5 2<br/>
样例2<br/>
3</div>
# 数据规模和约定

<div class="pdcont">　　2≤n≤1000, 1≤k≤30, k&lt;n，0≤xi,yi≤32000</div>

</div>