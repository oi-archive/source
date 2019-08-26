
# Description

<div class="content"><p><span style="font-size: medium">Farmer John最近得到了一些新的农场，他想新修一些道路使得他的所有农场可以经过原有的或是新修的道路互达（也就是说，从任一个农场都可以经过一些首尾相连道路到达剩下的所有农场）。有些农场之间原本就有道路相连。 所有N(1 &lt;= N &lt;= 1,000)个农场（用1..N顺次编号）在地图上都表示为坐标为(X_i, Y_i)的点(0 &lt;= X_i &lt;= 1,000,000；0 &lt;= Y_i &lt;= 1,000,000)，两个农场间道路的长度自然就是代表它们的点之间的距离。现在Farmer John也告诉了你农场间原有的M(1 &lt;= M &lt;= 1,000)条路分别连接了哪两个农场，他希望你计算一下，为了使得所有农场连通，他所需建造道路的最小总长是多少。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 2个用空格隔开的整数：N 和 M</span></p>
<p><span style="font-size: medium"> * 第2..N+1行: 第i+1行为2个用空格隔开的整数：X_i、Y_i * 第N+2..N+M+2行: 每行用2个以空格隔开的整数i、j描述了一条已有的道路， 这条道路连接了农场i和农场j </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出使所有农场连通所需建设道路的最小总长，保留2位小数，不必做 任何额外的取整操作。为了避免精度误差，计算农场间距离及答案时 请使用64位实型变量 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
1 1<br/>
3 1<br/>
2 3<br/>
4 3<br/>
1 4<br/>
<br/>
输入说明:<br/>
<br/>
    FJ一共有4个坐标分别为(1,1)，(3,1)，(2,3)，(4,3)的农场。农场1和农场<br/>
4之间原本就有道路相连。<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.00<br/>
<br/>
输出说明:<br/>
<br/>
    FJ选择在农场1和农场2间建一条长度为2.00的道路，在农场3和农场4间建一<br/>
条长度为2.00的道路。这样，所建道路的总长为4.00，并且这是所有方案中道路<br/>
总长最小的一种。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

