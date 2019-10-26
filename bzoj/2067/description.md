
# Description

<div class="content">String-Toys joint-stock 公司需要你帮他们解决一个问题. 他们想制造一个没有环的连通图模型.
每个图都是由一些顶点和特定数量的边构成. 每个顶点都可以连向许多的其他顶点.一个图是连通且无环的.
图是由许多的线做成的.一条线是一条连接图中两个顶点之间的路径.由于一些技术原因,两条线之间不能有重叠的部分,要保证图中任意一条边都被且仅被一条线所覆盖.由于一些技术原因,做一个这样的图的模型的费用取决于用了多少条线以及最长的那条的长度. (每条边的长度都为1.),给出对应的图,求出最少能用多少条线以及在用最少线的情况下最长的那根线最短可以为多少.
</div>

# Input

<div class="content">第一行仅包含一个数n – 顶点的总数, 2 &lt;= n &lt;= 10 000. 顶点从1 到 n进行编号. 接下来的n - 1 行描述这些边, 每行两个数a 和 b, 1 &lt;= a, b &lt;= n, a &lt;&gt; b. 表示顶点a和顶点b之间有一条边.
</div>

# Output

<div class="content">输出两个数,最少用多少条线以及在用最少线的情况下最长线最短可以为多少.
</div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
7 8<br/>
4 5<br/>
5 6<br/>
1 2<br/>
3 2<br/>
9 8<br/>
2 5<br/>
5 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 2<br/>
</span></div>

# Hint

<div class="content"><p><img border="0" src="/source/bzoj/2067/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIwNjcuanBn.jpg"/> <br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Stage 1">Stage 1</a></p></div>

