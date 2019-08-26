
# Description

<div class="content"><p><span style="font-size: medium">一个3*n的棋盘上，有一条蛇在棋盘上。从蛇头到蛇尾刚好是1~3*n。如下图是一合法方案。<br/>
</span></p>
<p><span style="font-size: medium"><img height="149" width="435" alt="" src="source/bzoj/3525/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNC9hYS5qcGc=.jpg"/></span></p>
<p><span style="font-size: medium">现在你只知道某几个位置上的数，其他位置都不确定。请构造出任意一组合法的蛇形图。<br/>
保证数据有解。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个数n。<br/>
接下来3行，每行n个数。<br/>
令第i行第j个数为a[i][j]<br/>
如果a[i][j]是0，则这一位不确定，否则这一位是a[i][j]。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出一个合法方案。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
0 0 5 0 17 0 0 0 21<br/>
8 0 0 3 16 0 0 25 0<br/>
0 0 0 0 0 0 0 0 23<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7 6 5 4 17 18 19 20 21<br/>
8 1 2 3 16 15 26 25 22<br/>
9 10 11 12 13 14 27 24 23<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">n≤1000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Dzy">By Dzy</a></p></div>

