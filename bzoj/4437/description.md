
# Description

<div class="content"><p>一座迷宫是由一个矩形网格铺上一种图案得到的。矩形网格有n行m列，每一个格子不是空的就是被覆盖的。如此就形成了一个无穷大的网格，且图案向四个方向无限循环。<br/>
    我们给每个格子编号(包括负整数),行数向下递增，列数向右递增，座标为(0,0)的单元格为原点。整个迷宫由复制图案到每个n×m的矩阵而成(没有旋转和镜像操作)。每个图案的左上角的单元格的行数可被n整除，列数可被m整除。原图案的左上角位于原点，右下角的座标为(n-1,m-1)。<br/>
    我们需从一个单元格出发，向上、下、左、右移动，经过一些空格，到达原点。<br/>
    你将被给出一个图案和一些出发点。确定从这些出发点出发是否能逃出迷宫。</p></div>

# Input

<div class="content"><p>第一行包括2个整数n和m(1&lt;=n,m&lt;=100)——图案的行数和列数。<br/>
接下来n行每行包括一个长度为m的字符串，表示图案的一行。“#”表示一个被覆盖的单元格，“.”表示未被覆盖的单元格。<br/>
接下来一行包括一个整数q——出发点的个数。<br/>
接下来q行，每行包括两个整数r和c(-109&lt;=r,c,&lt;=109)——出发点的座标。<br/>
原点和所有出发点都是空单元格。</p></div>

# Output

<div class="content"><p>输出包括q行。<br/>
对每个出发点，如果能过逃出迷宫，输出“yes”,否则输出“no”。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 9<br/>
．．＃＃＃＃＃．．<br/>
．．＃．．．＃．． <br/>
．．．．．．＃．． <br/>
．．＃＃＃＃＃．． <br/>
．．＃．．．．．． <br/>
．．＃．．．＃．． <br/>
5<br/>
1 4<br/>
5 4<br/>
1 -5<br/>
5 -5<br/>
-1000000000 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">yes<br/>
no<br/>
no<br/>
yes<br/>
yes<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

