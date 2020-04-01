
# Description

<div class="content"><div>
<div>曾经有一款流行的游戏，叫做InfinityLoop，先来简单的介绍一下这个游戏:</div>
<div>游戏在一个n×m的网格状棋盘上进行，其中有些小方格中会有水管，水管可能在方格某些方向的边界的中点有接口</div>
<div>，所有水管的粗细都相同，所以如果两个相邻方格的公共边界的中点都有接头，那么可以看作这两个接头互相连接</div>
<div>。水管有以下15种形状：</div>
<div><img src="/source/bzoj/5120/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcxMi92djIucG5n.png" width="430" height="228" alt=""/></div>
<div>游戏开始时，棋盘中水管可能存在漏水的地方。</div>
<div>形式化地:如果存在某个接头，没有和其它接头相连接，那么它就是一个漏水的地方。</div>
<div>玩家可以进行一种操作：选定一个含有非直线型水管的方格，将其中的水管绕方格中心顺时针或逆时针旋转90度。</div>
<div>直线型水管是指左图里中间一行的两种水管。</div>
<div>现给出一个初始局面，请问最少进行多少次操作可以使棋盘上不存在漏水的地方。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数n,m代表网格的大小。</div>
<div>接下来n行每行m数，每个数是[0,15]中的一个</div>
<div>你可以将其看作一个4位的二进制数，从低到高每一位分别代表初始局面中这个格子上、右、下、左方向上是否有水管接头。</div>
<div>特别地，如果这个数是000，则意味着这个位置没有水管。</div>
<div>比如3(0011(2))代表上和右有接头，也就是一个L型，而12(1100(2))代表下和左有接头，也就是将L型旋转180度。</div>
<div>n×m≤2000</div>
<p></p></div>

# Output

<div class="content"><div>输出共一行，表示最少操作次数。如果无法达成目标，输出-1</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
3 14 12<br/>
3 11 12</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p> 样例1棋盘如下</p><br/>
<div>旋转方法很显然，先将左上角虚线方格内的水管顺时针转90度</div><br/>
<div><img src="/source/bzoj/5120/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcxMi92djEucG5n.png" width="192" height="270" alt=""/></div><br/>
<div>然后右下角虚线方格内的水管逆时针旋转90度，这样就使得水管封闭了</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

