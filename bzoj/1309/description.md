
# Description

<div class="content">霸中由沙漠中的N个绿洲组成，没有三个绿洲是共线的。DYY住在其中的一个绿洲中，而他在每个绿洲里都有一个朋友。DYY想骑骆驼出去旅行一趟，拜访尽量多的朋友。这只骆驼非常固执，它只以它独特的方式前进：
离开一个绿洲后，它只沿一条直线前进，直到它到达另一个绿洲；
它只在绿洲里转弯，但它只朝右转（顺时针），并且角度在[0°,180°]内（它在一个绿洲只做一次转弯，也就是说，它不会转200°=100°+100°）；	它的路线不会交叉，也就是说，它不会经过任何一个点两次（除了出发点之外）。
请你帮助DYY设计一条路线，让他能访问尽量多的朋友。这条路线必须从DYY住的绿洲出发，最后回到原处。
</div>

# Input

<div class="content">第一行一个正数N ( 3 &lt;= N &lt;= 1 000) – 表示绿洲的个数. 
接下来第(i + 1)行两个数xi, yi – 描述第i个绿洲的坐标,所有的坐标值从 -16 000 到 16 000</div>

# Output

<div class="content">一行，输出最多能访问的朋友的个数。

</div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 1<br/>
-1 4<br/>
0 -1<br/>
4 1<br/>
0 3<br/>
1 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<img border="0" src="/source/bzoj/1309/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEzMDkuanBn.jpg"/><br/>
</span></div>

# Hint

<div class="content"><p>DDY最初在绿洲1,他的骆驼首先面朝绿洲2.<br/>
<br/>
对于30%的数据，N≤20<br/>
对于60%的数据，N≤200<br/>
对于100%的数据，N≤1000<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

