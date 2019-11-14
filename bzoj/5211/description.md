
# Description

<div class="content"><div>九条可怜是一个热爱出题的女孩子。今天可怜想要出一道和图论相关的题。在一张无向图G上，我们可以对它进行</div>
<div>一些非常有趣的变换，比如说对偶，又或者说取补。这样的操作往往可以赋予一些传统的问题新的活力。例如求补</div>
<div>图的连通性、补图的最短路等等，都是非常有趣的问题。最近可怜知道一种新的变换：求原图的线图(linegraph)</div>
<div>对于无向图G=&lt;V,E&gt;它的线图L(G)也是一个无向图：1:它的点集大小为|E|，每个点唯一对应着原图的一条边。2:两</div>
<div>个点之间有边当且仅当这两个点对应的边在原图上有公共点（注意不会有自环）。下图是一个简单的例子，左图是</div>
<div>原图，右图是它对应的线图。其中点1对应原图的边(1,2)，点2对应(1,4)，点3对应(1,3)，点4对应(3,4)</div>
<div><img src="/source/bzoj/5211/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy8xKDIpLnBuZw==.png" width="289" height="135" alt=""/></div>
<div>经过一些初步的摸索，可怜发现线图的性质要比补图复杂很多，其中突出的一点就是补图的补图会变回原图，而L(</div>
<div>L(G))在绝大部分情况下不等于G，甚至在大多数情况下它的点数和边数会以很快的速度增长。因此，可怜想要从最</div>
<div>简单的入手，即计算L<sup>k</sup>(G)的点数（L<sup>k</sup>(G)表示对G求k次线图）。然而遗憾的是，即使是这个问题，对可怜来说还是</div>
<div>太困难了，因此她进行了一定的弱化。她给出了一棵n个节点的树T，现在她想让你计算一下L<sup>k</sup>(T)的点数。</div>
<div></div></div>

# Input

<div class="content"><div>第一行输入两个整数n,k，表示树的点数以及连续求线图的次数。</div>
<div>接下来n?1行每行两个整数u,v表示树上的一条边。</div>
<div>2 ≤ n ≤ 5000</div>
<div>k&lt;=9</div>
<div></div></div>

# Output

<div class="content"><p>输出一行一个整数，表示答案对998244353取模后的值</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 2<br/>
2 3<br/>
2 5<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p> <img src="/source/bzoj/5211/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy8yLmpwZw==.jpg" width="613" height="251" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

