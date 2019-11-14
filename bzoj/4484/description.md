
# Description

<div class="content"><p>【故事背景】<br/>
还记得去年JYY所研究的强连通分量的问题吗？去年的题目里，JYY研究了对于有向图的“加边”问题。对于图论有着强烈兴趣的JYY，今年又琢磨起了“删边”的问题。<br/>
【问题描述】<br/>
对于一个N个点（每个点从1到N编号），M条边的有向图，JYY发现，如果从图中删去一些边，那么原图的连通性会发生改变；而也有一些边，删去之后图的连通性并不会发生改变。<br/>
JYY想知道，如果想要使得原图任意两点的连通性保持不变，我们最多能删掉多少条边呢？<br/>
为了简化一下大家的工作量，这次JYY保证他给定的有向图一定是一个有向无环图（JYY：大家经过去年的问题，都知道对于给任意有向图的问题，最后都能转化为有向无环图上的问题，所以今年JYY就干脆简化一下大家的工作）。</p></div>

# Input

<div class="content"><p>输入一行包含两个正整数N和M。<br/>
接下来M行，每行包含两个1到N之间的正整数x_i和y_i，表示图中存在一条从x_i到y_i的有向边。<br/>
输入数据保证，任意两点间只会有至多一条边存在。<br/>
N&lt;=30,000,M&lt;=100,000</p></div>

# Output

<div class="content"><p>输出一行包含一个整数，表示JYY最多可以删掉的边数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
1 2<br/>
2 3<br/>
3 5<br/>
4 5<br/>
1 5<br/>
1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

