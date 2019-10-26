
# Description

<div class="content"><p><span style="font-size: medium">给定平面里的 N 个矩形, 每个矩形的边都是和坐标系平行的.<br/>
并且满足 每个矩形的下面的边 和 x轴 重合.<br/>
</span><span style="font-size: medium">从 N 个矩形中删除最多的矩形, 使得 矩形并的区域的边界 保持不变.</span></p>
<p><span style="font-size: medium"><img height="277" alt="" width="690" src="/source/bzoj/3089/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwMy8xKDMpLmpwZw==.jpg"/></span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">    第1行: 一个整数 N (1 &lt;= N &lt;= 100, 000)<br/>
    第2..N+1行: 每行3个整数 X, W, H, 表示一个矩形.<br/>
                X 表示矩形左边界的x坐标.<br/>
                W 表示矩形的宽度 (右边的x坐标 - 左边的x坐标)<br/>
                H 表示矩形的高度 (上边的y坐标 - 下边的y坐标)</span></p>
<p><span style="font-size: medium">                没有两个矩形是 完全重合 (X W H 都完全一样) 的.<br/>
                0 &lt;= X, W, H &lt;= 10^9<br/>
                所有矩形标号为 1..N</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
    第1行: 最少留下的矩形数量 B<br/>
    </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
15 8 4<br/>
10 8 3<br/>
25 3 7<br/>
3 9 5<br/>
1 5 3<br/>
7 2 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

