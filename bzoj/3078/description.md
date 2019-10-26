
# Description

<div class="content"><div><span style="font-size: medium">Alice和Bob在如上图的棋盘中移动一个同一个棋子，轮流行动，Alice先手。每次可以上下左右移动，不能撞障碍，不能走已经走过的格子。不能行动的人就输了。对于每个起始位置，判断先手是否必胜。</span></div>
<div><span style="font-size: medium"><img height="276" width="444" alt="" src="/source/bzoj/3078/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwMy8yMigxKS5qcGc=.jpg"/></span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行(0&lt;=N,M&lt;=100)。接下来是N行M列的矩阵，”.”代表空地，”X”代表障碍物。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出行列，’X’代表障碍，’A’代表先手必胜，’B’代表先手必败。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 1<br/>
.<br/>
3 3<br/>
...<br/>
.X.<br/>
...<br/>
1 4<br/>
....<br/>
3 3<br/>
X.X<br/>
...<br/>
X.X<br/>
5 8<br/>
........<br/>
.XX.XXX.<br/>
.X..X...<br/>
.X.XX.X.<br/>
........<br/>
0 0<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">B<br/>
 <br/>
AAA<br/>
AXA<br/>
AAA<br/>
 <br/>
AAAA<br/>
 <br/>
XBX<br/>
BAB<br/>
XBX<br/>
 <br/>
BABABABA<br/>
AXXBXXXB<br/>
BXBAXABA<br/>
AXAXXBXB<br/>
BABABABA<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

