
# Description

<div class="content">C国的地图可以看成一个由N个点组成的树，其中每个点代表C国的一个城市，而每条边代表连接城市之间的街道。C国的街道都是平行于坐标轴的，因此每个城市最多只有4条街道与它连接，即上下左右四个方向最多只有一个城市与它通过街道所连接。现在你来到了C国旅游，你希望开车遍历尽可能多的C国的街道，不过很快你就发现如果不停地转弯地话实在太耽误时间。“转弯”的定义是在某个城市由水平方向的道路开向了垂直方向的道路或垂直方向的道路转向了水平方向的道路。所以你想找一条最长的路径使得任何一个城市最多经过一次且转弯的次数不超过K次，并且你想知道有多少条满足条件的最长的路径。
</div>

# Input

<div class="content">第一行有两个数N, K分别表示城市的个数以及最多的转弯次数，其中城市的编号为1 ~ n。
接下来n行，每行四个数l, d, r, u分别表示第i个城市左, 下，右，上所连接的城市。如果是0的话表示第i个城市在这个方向上没有与其它的城市相连。
</div>

# Output

<div class="content">两个正整数分别表示满足条件的路径长度的最大值以及有多少条满足条件的路径。
</div>

# Sample Input

<div class="content"><span class="sampledata">12 4<br/>
0 2 3 4<br/>
0 0 0 1<br/>
1 0 0 0<br/>
5 1 0 0<br/>
6 0 4 0<br/>
0 7 5 0<br/>
8 0 9 6<br/>
10 11 7 12<br/>
7 0 0 0<br/>
0 0 8 0<br/>
0 0 0 8<br/>
0 8 0 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7 4<br/>
数据范围<br/>
N &lt;= 10000, 0 &lt;= K &lt;= N<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

