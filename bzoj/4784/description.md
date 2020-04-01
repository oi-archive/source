
# Description

<div class="content"><div>如果一个无自环无重边无向连通图的任意一条边最多属于一个简单环，我们就称之为仙人掌。所谓简单环即不经过</div>
<div>重复的结点的环。</div>
<div><img src="/source/bzoj/4784/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwMy8xMS5qcGc=.jpg" width="460" height="224" alt=""/></div>
<div>现在九条可怜手上有一张无自环无重边的无向连通图，但是她觉得这张图中的边数太少了，所以她想要在图上连上</div>
<div>一些新的边。同时为了方便的存储这张无向图，图中的边数又不能太多。经过权衡，她想要加边后得到的图为一棵</div>
<div>仙人掌。不难发现合法的加边方案有很多，可怜想要知道总共有多少不同的加边方案。两个加边方案是不同的当且</div>
<div>仅当一个方案中存在一条另一个方案中没有的边。</div>
<div></div></div>

# Input

<div class="content"><div>多组数据，第一行输入一个整数T表示数据组数。</div>
<div>每组数据第一行输入两个整数n,m，表示图中的点数与边数。</div>
<div>接下来m行，每行两个整数u,v(1≤u,v≤n,u!=v)表示图中的一条边。保证输入的图</div>
<div>联通且没有自环与重边</div>
<div>Sigma(n)&lt;=5*10^5,m&lt;=10^6,1&lt;=m&lt;=n*(n-1)/2</div></div>

# Output

<div class="content"><div>对于每组数据，输出一个整数表示方案数，当然方案数可能很大，请对998244353取模后</div>
<div>输出。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 2<br/>
1 2<br/>
1 3<br/>
5 4<br/>
1 2<br/>
2 3<br/>
2 4<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
8<br/>
对于第一组样例合法加边的方案有 {}, {(2,3)}，共 2 种。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

