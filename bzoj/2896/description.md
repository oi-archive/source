
# Description

<div class="content"><div><span style="font-size: medium">有一张N个点，M条边的无向图，如果去掉某条边后，图中A,B两点不可互达，那么我们称这条边是A,B两点间的桥。现在我们随时有可能永久删除某条边，或者询问你某两点间有几条边是桥，请你做出回答。另外任意时刻我们都会保持图的连通性，这点你放心。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行n，m</span></div>
<div><span style="font-size: medium">接下来m行表示m条边</span></div>
<div><span style="font-size: medium">然后每行三个整数c，a，b如果c=0表示边ab被永久删除，如果c=1表示询问ab间有几条边是桥。如果c=-1则输入数据结束。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">对于每一个询问，给出你的结果。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2<br/>
1 3<br/>
3 4<br/>
4 5<br/>
4 2<br/>
1 1 5<br/>
0 4 2<br/>
1 5 1<br/>
-1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
Data Limit<br/>
对于30%的数据，有1 ≤ N ≤ 1000，1 ≤ M ≤ 1000，询问数加删除数不多于1000.<br/>
对于100%的数据，有1 ≤ N ≤ 30000，1 ≤ M ≤ 100000，询问数加删除数不多于40000<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

