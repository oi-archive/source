
# Description

<div class="content"><p>　　一个有向图G=(V,E)称为半连通的(Semi-Connected)，如果满足：?u,v∈V，满足u→v或v→u，即对于图中任意<br/>
两点u，v,存在一条u到v的有向路径或者从v到u的有向路径。若G&#39;=(V&#39;,E&#39;)满足V&#39;?V，E&#39;是E中所有跟V&#39;有关的边，<br/>
则称G&#39;是G的一个导出子图。若G&#39;是G的导出子图，且G&#39;半连通，则称G&#39;为G的半连通子图。若G&#39;是G所有半连通子图<br/>
中包含节点数最多的，则称G&#39;是G的最大半连通子图。给定一个有向图G，请求出G的最大半连通子图拥有的节点数K<br/>
，以及不同的最大半连通子图的数目C。由于C可能比较大，仅要求输出C对X的余数。</p></div>

# Input

<div class="content"><p>　　第一行包含两个整数N，M，X。N，M分别表示图G的点数与边数，X的意义如上文所述接下来M行，每行两个正整<br/>
数a, b，表示一条有向边(a, b)。图中的每个点将编号为1,2,3…N，保证输入中同一个(a,b)不会出现两次。N ≤1<br/>
00000, M ≤1000000；对于100%的数据， X ≤10^8</p></div>

# Output

<div class="content"><p>　　应包含两行，第一行包含一个整数K。第二行包含整数C Mod X.</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6 20070603<br/>
1 2<br/>
2 1<br/>
1 3<br/>
2 4<br/>
5 6<br/>
6 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

