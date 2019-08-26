
# Description

<div class="content"><div>有一棵n个结点的树，每条边有个长度leni (1≤leni≤10000)。</div>
<div>有q个点集，每个点集给定两个整数u,d (1≤u≤n,1≤d≤109)，表示所有与u的距离不超过d的点（包括u）在这个点集中。</div>
<div>两个点之间的距离为它们之间的最短路径的长度。</div>
<div></div>
<div>要求构造一个DAG（有向无环图），满足：</div>
<div>1、这个DAG至少有n+q个点，至多有1200000(1.2×106)个点和2400000(2.4×106)条边</div>
<div>2、对于每一条边u→v，u&gt;n 且 u≠v</div>
<div>3、对于第i (1≤i≤q)个点集的每一个点x，第n+i个点到第x个点都有且仅有一条路径</div>
<div>4、对于不在第i (1≤i≤q)个点集的每一个点x，第n+i个点到第x个点都不存在路径</div>
<div></div>
<div>由于一些奇怪的原因，树上可能多了若干条边，但是这些边覆盖的树链不会重合，且不会存在自环。（即这棵树是仙人掌）</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行三个整数n,m,q，其中m表示这棵仙人掌上一共有m条边。</div>
<div>接下来m行，每行三个整数u,v,len，表示u和v之间有一条长度为len的无向边。</div>
<div>接下来q行，每行两个整数u,d，第i行表示第i个点集。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行两个整数V,E，表示你构造的DAG的点数和边数。</div>
<div>接下来E行，每行两个整数u,v，表示u到v有一条有向边。</div>
<div></div>
<div>！！！请注意输出文件的大小，不能超过32MB，否则会显示TLE！！！</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 9 5<br/>
2 1 9553<br/>
3 2 8499<br/>
4 3 5171<br/>
5 1 7123<br/>
6 3 1904<br/>
7 5 5526<br/>
8 7 5853<br/>
9 6 6635<br/>
10 8 7858<br/>
6 4981<br/>
7 14400<br/>
3 21290<br/>
4 9451<br/>
10 16609</span></div>

# Sample Output

<div class="content"><span class="sampledata">15 19<br/>
11 6<br/>
11 3<br/>
12 7<br/>
12 5<br/>
12 1<br/>
12 8<br/>
12 10<br/>
13 3<br/>
13 6<br/>
13 9<br/>
13 4<br/>
13 2<br/>
13 1<br/>
14 4<br/>
14 3<br/>
14 6<br/>
15 10<br/>
15 8<br/>
15 7</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=10000,N-1&lt;=m&lt;=2*N-2,Q&lt;=10000</p><br/>
<p>尚无SPJ，请不要提交!</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年集训队互测">2015年集训队互测</a></p></div>

