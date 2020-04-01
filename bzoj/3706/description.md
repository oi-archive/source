
# Description

<div class="content"><p><span style="font-size: medium">给一张无向图，边有黑白两种颜色，现在你有一堆反色刷，可以从任意点开始刷，经过若干条边后回到起点。<br/>
现在要询问至少需要多少个反色刷可以使这张图所有边都变成白色。<br/>
因为某种原因，边的颜色是会改变的，于是。。<br/>
需要支持以下操作：<br/>
1 x  把第x条边反色（编号从0~m-1）<br/>
2   询问当前图中最少需要多少个反色刷<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行两个整数n m表示这张图有n个点m条边<br/>
接下来m行 每行3个整数 u v c表示一条无向边和这条边的颜色(0为白色 1为黑色)<br/>
接下来一个整数q 表示有q个操作<br/>
接下来q行为操作 描述如上</font></p></div>

# Output

<div class="content"><p><font size="4">对于每个询问 输出一行一个整数<br/>
表示最少需要的反色刷个数 如果没有合法方案输出-1</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6<br/>
1 2 1<br/>
2 3 1<br/>
1 3 1<br/>
4 5 1<br/>
5 6 1<br/>
4 6 1<br/>
14<br/>
2<br/>
1 0<br/>
2<br/>
1 1<br/>
1 2<br/>
2<br/>
1 3<br/>
1 4<br/>
1 5<br/>
2<br/>
1 3<br/>
1 4<br/>
1 5<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
-1<br/>
1<br/>
0<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">100%  n,m,q &lt;= 1000000, c &lt; 2，没有重边自环</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

