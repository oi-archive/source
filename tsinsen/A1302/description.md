<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　平面上有n个点。现在有m次询问，每次给定一个点(px, py)和一个整数k，输出n个点中离(px, py)的距离第k大的点的标号。如果有两个(或多个)点距离(px, py)相同，那么认为标号较小的点距离较大。</div>
# 输入格式

<div class="pdcont">　　第一行，一个整数n，表示点的个数。<br/>
　　下面n行，每行两个整数x_i, y_i，表示n个点的坐标。点的标号按照输入顺序，分别为1..n。<br/>
　　下面一行，一个整数m，表示询问个数。<br/>
　　下面m行，每行三个整数px_i, py_i, k_i，表示一个询问。</div>
# 输出格式

<div class="pdcont">　　m行，每行一个整数，表示相应的询问的答案。</div>
# 样例输入

<div class="pddata">3<br/>
0 0<br/>
0 1<br/>
0 2<br/>
3<br/>
1 1 2<br/>
0 0 3<br/>
0 1 1</div>
# 样例输出

<div class="pddata">3<br/>
1<br/>
1</div>
# 数据规模和约定

<div class="pdcont">　　50%的数据中，n个点的坐标在某范围内随机分布。<br/>
　　100%的数据中，n&lt;=10^5, m&lt;=10^4, 1&lt;=k&lt;=20，所有点(包括询问的点)的坐标满足绝对值&lt;=10^9，n个点中任意两点坐标不同，m个询问的点的坐标在某范围内随机分布。</div>

</div>