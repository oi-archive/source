
# Description

<div class="content"><div>如果一个无向连通图的任意一条边最多属于一个简单环，我们就称之为仙人掌。所谓简单环即不经过重复的结点的环。</div>
<div>什么是仙人掌</div>
<div><img src="/source/bzoj/4252/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwOC8yMi5QTkc=.PNG" width="547" height="243" alt=""/></div>
<div></div>
<div>现给定一棵仙人掌，每条边有一个正整数权值，每次给 k 个点（可以存在相同点），问从它们中选出两个点（可以相同），它们之间最短路的最大值是多少。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个非负整数 n,m，表示仙人掌的点数和边数。</div>
<div>接下来 m 行，每行三个正整数 v,u,w (1≤v,u≤n)，表示 v 与 u 之间有一条边权为 w 的无向边。点从 1 开始编号。</div>
<div>保证输入的图是一棵仙人掌，保证没有自环，但可能有重边。</div>
<div>接下来一行一个非负整数 Q，表示询问个数。</div>
<div>接下来 Q 行每行第一个数是正整数 cnt 表示点数，接下来 cnt 个数表示给定的点。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对每个询问输出一个数，表示该询问对应的最大值。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 14<br/>
10 7 1<br/>
3 8 7<br/>
1 6 9<br/>
7 2 10<br/>
8 9 9<br/>
1 7 1<br/>
8 5 2<br/>
4 5 4<br/>
1 7 4<br/>
2 9 8<br/>
9 3 3<br/>
8 4 2<br/>
1 6 5<br/>
7 9 10<br/>
6<br/>
2 9 5<br/>
2 8 10<br/>
3 8 7 6<br/>
2 6 4<br/>
3 3 4 2<br/>
1 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
20<br/>
25<br/>
27<br/>
19<br/>
0</span></div>

# Hint

<div class="content"><p></p><div>前五个询问的答案路径分别为(如果有重边则显然走较短的边):</div><br/>
<div></div><br/>
<div>9→8→5</div><br/>
<div>8→9→7→10</div><br/>
<div>8→9→7→1→6</div><br/>
<div>4→8→9→7→1→6</div><br/>
<div>2→9→8→4</div><br/>
<div>最后一个询问的答案显然是0。</div><br/>
<div></div><br/>
<div>边权不超过 2^31−1。</div><br/>
<div>对于 100% 的数据，n,tot≤300000。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By matthew99">By matthew99</a></p></div>

