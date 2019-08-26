
# Description

<div class="content"><div>定义任意两点之间存在唯一路径的无向图是树。对于一棵n个点的树，如果删掉某个点u之后每个连通块的大小均不</div>
<div>超过n/2，那么称u为这棵树的重心。现在有一棵n个点的树T，利用过程P来构造一个n个点的有向图G，初始G没有边</div>
<div>。现在对T调用过程P，P的内容如下：</div>
<div>1:删去u，对每个连通块递归调用过程P；</div>
<div>2:对每个连通块，如果它的标号最小的重心为v，那么在图G中连一条u到v的有向边。</div>
<div>3:现在小Q同学手里有一个图G，但是不记得原来T的样子了，希望你能通过G来恢复T，但是可能得到的T会有很多种</div>
<div>你只需要告诉小Q同学可能的T的个数。</div>
<div>两棵树被认为是不同的，当且仅当存在一对点(u,v)，使得u和v在一棵树中有边，在另一棵树中没有边。</div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><p> 第一行是一个整数T(1≤T≤1000)，表示测试数据的组数。</p>
<div>对于每组测试数据：</div>
<div>第一行是两个整数n和m(2≤n,m≤100000)，表示G的点数的边数。</div>
<div>接下来m行，每行是两个整数u和v(1≤u,v≤n)，表示有一条从u到v的有向边。</div>
<div>保证对于每组测试数据，至少存在一棵树T，使得对T调用过程P之后可以得到G</div>
<div>并且所有测试数据的n之和、m之和均不超过10^6。</div></div>

# Output

<div class="content"><p>对于每组测试数据，输出一行一个非负整数，表示这组数据的答案对(10^9+7)取模的值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 2<br/>
1 2<br/>
1 3<br/>
4 3<br/>
1 3<br/>
2 1<br/>
2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

