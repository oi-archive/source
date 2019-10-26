
# Description

<div class="content"><p><span style="font-size: medium">在平面直角坐标系中有n条互不相交(没有公共点)且所在直线不会经过(0,0)的线段。有一个人站在(0,0)，他的视野是360度的。但是他在某一个方向上的视野会被该方向上碰到的第一条线段所阻挡，问他能看到的区域面积有多大（数据保证是有限面积）。如下图（样例），可以看到的面积就是11。<br/>
<img alt="" width="203" height="205" src="/source/bzoj/2640/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMy9mZigxKS5qcGc=.jpg"/></span></p>
<p></p>
<p><span style="font-size: medium">　　为了加大难度，他想知道，在删除一条线段的情况下能看到最大多大的面积（不保证是有限面积）。<br/>
　　进一步，他还想知道，在删除两条线段的情况下能看到最大多大的面积（不保证是有限面积）。<br/>
</span></p></div>

# Input

<div class="content"><div class="pdcont"><span style="font-size: medium">　　第一行一个整数n表示线段条数。<br/>
　　接下来n行，每行四个整数x1,y1,x2,y2表示一条线段两个端点的坐标。<br/>
</span></div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　第一行一个保留两位小数的实数，表示可见区域的面积。<br/>
　　第二行两种可能，如果删除一条线段以后能使得看到的区域有无限大输出”infinite”，否则输出一个保留两位小数的实数，表示这种情况下能看到的最大面积。<br/>
　　第三行两种可能，如果删除两条线段以后能使得看到的区域有无限大输出”infinite”，否则输出一个保留两位小数的实数，表示这种情况下能看到的最大面积。<br/>
</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
-1 -1 0 -1<br/>
0 -2 1 -1<br/>
-1 1 0 2<br/>
0 1 1 1<br/>
2 -2 2 2<br/>
-2 -2 -2 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11.00<br/>
infinite<br/>
infinite<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模和约定<br/><br/>
　　对于所有数据<br/><br/>
　　1&lt;=n&lt;=50000<br/><br/>
　　坐标的绝对值&lt;=10^3<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

