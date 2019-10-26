
# Description

<div class="content"><div>安全有限公司是一家生产高品质保险箱的公司。它最新的发明是一种使用激光穿过一个有几面镜子的矩形网格的光学封闭机械。</div>
<div><img src="/source/bzoj/3981/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC9nZ2dnLmpwZw==.jpg" width="746" height="202" alt=""/></div>
<div>当激光被激活后，从矩形网格的最上方一行的左侧水平射入。每当激光束击中一面镜子，/和\二者之一，就会以45度角被反射。如果激光束从矩形网格底部一行的右侧水平射出（见上图左），那么安全检测成功，保险箱打开。否则保险箱依然关闭并发出警报。</div>
<div>每个保险箱有一面镜子丢失来防止激光束成功穿过网格（见上图右）。保险箱有一个能让用户把一面镜子放到任意一个空的网格上。一个合法的用户会知道正确的放镜子的位置和放置镜子的正确方向（上图右是第4行第3列，方向是/），因此可以打开保险箱。而不知道这点的用户在有大型网格的保险箱中很难猜对。</div>
<div>你的工作是确定一个保险箱事实上是安全的。一个安全的保险箱不会再不插入镜子的情况下打开，并至少存在一个位置和正确方向的镜子在插入后保险箱能正确打开。事实上可能有多个这样的位置和方向。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>每组数组描述了一个单独的保险箱，开头一行包含了四个整数R,C,M,N，(1&lt;=R,C&lt;=1000000,0&lt;=M,N&lt;=200000)。该机械的网格有r行c列。</div>
<div>
<div>接下来有M行，每行包含两个整数RI，CI，指明有一个/镜子在第Ri行，CI列。接下来N行以相同方式指明N面\镜子的位置。M+N面镜子的位置两两不同。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>对于每组测试数组，在测试编号后紧跟：</div>
<div>l 0 如果不插入镜子保险箱就会被打开。</div>
<div>l K,R,C 如果保险箱不插入一面镜子就不会被打开，K是恰好能打开保险箱的插入位置的数量，R,C是字典序最小的正确插入位置。如果一个位置插入/或\都能正确打开，只算一次。</div>
<div>l impossible 无论插入或不插入镜子都不能打开</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6 1 4<br/>
2 3<br/>
1 2<br/>
2 5<br/>
4 2<br/>
5 5<br/>
100 100 0 2<br/>
1 77<br/>
100 77<br/>
100 100 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 2 4 3<br/>
Case 2: 0<br/>
Case 3: impossible</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据,1&lt;=R,C&lt;=1000000,1&lt;=N,M&lt;=200000</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

