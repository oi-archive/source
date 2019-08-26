
# Description

<div class="content">Alice和Bob在玩这样一种游戏：首先，Alice画一个N个顶点M条边的有向图,然后让Bob删去图中所有的边。规则是每步Bob选择一个顶点，然后或者所有指向这个顶点的有向边被删去(操作一)，或者所有以这个顶点为起始的有向边被删去(操作二)。
Alice分配两种代价到每一个顶点: Wi+ 和 Wi-. 如果Bob对顶点i执行操作一,那么他将花费$Wi+，反之他将花费$Wi-
请你试着帮Bob找出删去图中所有边的最小花费。
</div>

# Input

<div class="content">每组输入数据第一行包括N，M(1 &lt;= N &lt;= 100, 1 &lt;= M &lt;= 5000).第二行包括N个整数Wi+.第三行包括N个整数Wi-.所有花费都是正的且不超过10^6.紧跟着M行，每行包括两个整数a, b表示由a向b连接一条有向边.注意，两个顶点间可能有不止一条边，且图中亦存在环.
</div>

# Output

<div class="content">输出数据第一行包括一个整数W,Bob的最小花费</div>

# Sample Input

<div class="content"><span class="sampledata">3 6<br/>
1 2 3<br/>
4 2 1<br/>
1 2<br/>
1 1<br/>
3 2<br/>
1 2<br/>
3 1<br/>
2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Northeastern Europe 2003, Northern Subregion">Northeastern Europe 2003, Northern Subregion</a></p></div>

