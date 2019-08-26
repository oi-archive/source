
# Description

<div class="content"><div>出版地图并不是一件容易的事。首先你需要通过一些适当的变换来在一个二维平面上显示出地球的“球”的形状，然后另一个问题出现了——最优质的地图太大了，以至于不能被印在一页纸上。为了解决这个问题，地图出版者经常将地图分成若干矩形部分，并在同一页的各个矩形砖上打印各个部分。在本题中，你将验证以上的“平铺”过程。</div>
<div>国际地图出版公司（ICPC）需要通过减少用于打印地图的砖数来最小化他们的打印成本。即使对于固定的砖块大小（由页面大小决定）与地图比例尺，你仍然可以通过调整矩形砖网格的位置来进行优化。</div>
<div>图1左侧是一种用14个矩形砖来覆盖一个地图区域的方法。右侧显示了如何在不改变矩形砖的大小或方向的情况下，只用10个砖来覆盖同一区域。</div>
<div><img src="source/bzoj/3970/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC8xMTExLnBuZw==.png" width="779" height="421" alt=""/></div>
<div></div>
<div></div>
<div>图1：两种平铺德州地图的方法</div>
<div>你的任务是帮助ICPC找到为了覆盖指定的区域，最少需要多少矩形砖。为简化问题，假定这个指定的区域是一个闭合的多边形，且不自交。</div>
<div>注意这些砖组成的矩形网格必须与X轴和Y轴平行，也就是，他们互相接触的部分只能是整条边，而且不能旋转。此外，虽然输入的所有坐标都是整数，但矩形砖可能位于非整数坐标上。</div>
<div>这个多边形可能碰到矩形网格的边缘线（比如样例2）。但是，为了避免浮点误差，你可以假设当这个多边形向外移动不超过10-6的距离时，答案不会变化。</div>
<p></p></div>

# Input

<div class="content"><div>输入包含一组数据。第一行三个整数：n、xs、ys，其中n为多边形的顶点数，xs和ys为每个矩形砖在X轴和Y轴方向上的长度。接下来n行，每行两个整数x和y，表示多边形的各个顶点的坐标。给出的顶点顺序可能按照逆时针，也可能按照顺时针。</div>
<p></p></div>

# Output

<div class="content"><div>为了覆盖这个多边形，最少需要的矩形砖数目。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">12 9 9<br/>
1 8<br/>
1 16<br/>
6 16<br/>
9 29<br/>
19 31<br/>
23 24<br/>
30 23<br/>
29 18<br/>
20 12<br/>
22 8<br/>
14 0<br/>
14 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
</span></div>

# Hint

<div class="content"><p></p><div>3&lt;=n&lt;=50，1&lt;=xs, ys&lt;=100，0&lt;=x&lt;=10xs，0&lt;=y&lt;=10ys。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

