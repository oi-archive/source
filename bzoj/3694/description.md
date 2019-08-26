
# Description

<div class="content"><div><span style="font-size: medium">给出一个n个点m条边的无向图，n个点的编号从1~n，定义源点为1。定义最短路树如下：从源点1经过边集T到任意一点i有且仅有一条路径，且这条路径是整个图1到i的最短路径，边集T构成最短路树。</span><span style="font-size: medium"> 给出最短路树，求对于除了源点1外的每个点i，求最短路，要求不经过给出的最短路树上的1到i的路径的最后一条边。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行包含两个数n和m，表示图中有n个点和m条边。</span></div>
<div><span style="font-size: medium">接下来m行，每行有四个数ai，bi，li，ti，表示图中第i条边连接ai和bi权值为li，ti为1表示这条边是最短路树上的边，ti为0表示不是最短路树上的边。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出n-1个数，第i个数表示从1到i+1的要求的最短路。无法到达输出-1。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 9<br/>
3 1 3 1<br/>
1 4 2 1<br/>
2 1 6 0<br/>
2 3 4 0<br/>
5 2 3 0<br/>
3 2 2 1<br/>
5 3 1 1<br/>
3 5 2 0<br/>
4 5 4 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 7 8 5<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"> 对于100%的数据，n≤4000，m≤100000，1≤li≤100000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

