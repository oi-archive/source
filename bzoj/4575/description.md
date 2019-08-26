
# Description

<div class="content"><div>
<div>小Y是一个充满智慧的女孩子，但是她只会使用串并联的方法计算两个节点之间的电阻。现在小Y有一个电阻网络问</div>
<div>有多少点对u,v(u≠v)之间的电阻可以用串并联的方法计算出来。我们来形式化地定义一下点对u,v(u≠v)之间的电</div>
<div>阻能否用串并联的方法计算出来。首先我们把电阻网络看成一个n个点m条边的图（每个电阻对应一条边）。令S表</div>
<div>示从u到v的所有简单路径(不经过重复的点的路径)上点的并集，也就是对于一个点x，如果存在一条从u到v的简单</div>
<div>路径经过这个点，那么它就在集合S中。如果S非空且S的导出子图是u,v为端点的二端串并联图，那么u,v之间的电</div>
<div>阻就能用串并联方法计算。一个有两个不同端点s,t的图被称为二端图，其中一个称为源点，另一个称为汇点。两</div>
<div>个二端图X,Y并联(parallelcomposition)是指建一个新图，把X和Y的源点和汇点分别合并起来。两个二端图X,Y串</div>
<div>联(seriescomposition)是指建一个新图，把X的汇点和Y的源点合并起来。由若干个两个点一条边的二端图经过一</div>
<div>系列串并联变化之后形成的图称为二端串并联图。集合S的导出子图点集为S，边集由原图中两个端点都在S中的边</div>
<div>构成</div>
</div></div>

# Input

<div class="content"><div>第一行包含2个正整数n,m，表示电阻网络中的节点数和电阻数。接下来m行，每行包含2个正整数u,v(1≤u,v≤n,u</div>
<div>≠v)，表示有一个电阻在节点u和v之间</div></div>

# Output

<div class="content"><p>输出共1行，表示答案，即有多少点对之间的电阻可以使用串并联的方法计算出来。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 3<br/>
2 4<br/>
5 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
//可行的点对有(1,2),(1,3),(1,4),(2,3),(2,4),(5,6)。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

