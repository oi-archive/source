
# Description

<div class="content">Byteotia 是一个被海洋环绕的岛屿. 岛屿上有很多湖泊. 在这些湖泊上又有一些小岛,小岛上可能又有湖泊和更小的岛. 海洋的级别为0. Byteotia 级别为1. 在Byteotian 上的湖泊的级别为2 ., 如果一个湖泊在一个级别为w的岛屿上,那么这个湖泊的级别为w+1,类似的如果一个岛屿被一个级别为j的湖泊环绕上,那么这个岛屿的级别为j+1. 所有湖泊和岛屿的海岸线都是平行或垂直于坐标轴的. 没有两条海岸线重合或相交. 我们想求出级别最高的那个湖泊或者岛屿的级别. 
</div>

# Input

<div class="content">第一行一个整数n, 表示岛屿和湖泊的总数, 1 &lt;= n &lt;= 40000. 接下来每行描述一个岛屿或者湖泊. 每行首先一个偶数, k, 表示该海岸线包含有多少个顶点, 4 &lt;= k &lt;= 10000. 接下来k 个整数: x1, x2, ..., xk, 0 &lt;= xi &lt;= 108. 这些点的坐标分别为(x1, x2), (x3, x2), (x3, x4), (x5, x4), ... (xk-1, xk), (x1, xk). 他们按照逆时针顺序构成多边形: 
•	一个湖泊的海岸线在它所在的岛屿的海岸线给出后再给出, 
•	一个岛屿的海岸线在它被环绕的湖泊的海岸线给出后再给出. 
地图上不会超过有200,000 个点. 
</div>

# Output

<div class="content">一个整数表示最高级别. 
</div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
4 1 0 17 12<br/>
16 10 4 16 11 2 4 8 2 3 3 2 1 16 3 15 2<br/>
8 8 10 3 5 12 8 11 6<br/>
6 10 9 15 10 9 7<br/>
4 4 6 7 9<br/>
4 6 8 5 7<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=STAGE 3">STAGE 3</a></p></div>

