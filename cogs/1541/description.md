# 题目描述


<h3>
【题目描述】
</h3>
<p>
<img src="/upload/image/20140306/20140306181624_71222.jpg" alt=""/> 
</p>
<p>
Iset塔（高度215米，叶卡捷琳堡第二高楼）很快就要投入运营了，但在建筑中还没有安装计算机网络。这个网络应该非常健壮，有许多的分叉。塔中有N个节点，它们应该被连接到网络中。计划用M条无向边连接这些节点，两个节点之间最多只有一条边。为了节省时间，决定只修建必须的N-1条边，而剩余的电线将在开业典礼后铺设。为了让网络高效，它必须满足一个额外条件：它节点之间的最大距离必须尽可能小。两个节点A,B之间的距离是A,B之间路径的边数。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有两个整数N(2&lt;=N&lt;=100)和M(1&lt;=M&lt;=10000)。接下来的M行描述了最初计划的网络。每行有两个整数，即两个直接相连的节点。节点从1到N编号。假定这个网络是连通的，并且没有节点连接到自身。
</p>
<h3>
【输出格式】
</h3>
<p>
输出N-1行，即开业前必须铺设的网络（按照相同的格式）。
</p>
<h3>
【样例输入】
</h3>
<p>
4 4
</p>
<p>
1 2
</p>
<p>
2 3
</p>
<p>
2 4
</p>
<p>
3 4
</p>
<h3>
【样例输出】
</h3>
<p>
1 2
</p>
<p>
2 3
</p>
<p>
2 4
</p>
<h3>
【提示】
</h3>
<p>
对于30%的数据，1&lt;=N&lt;=10
</p>
<p>
对于100%的数据，范围如题中所示
</p>
<h3>
【来源】
</h3>
<p>
<span style="font-family:serif;background-color:white;font-size:16px;font-weight:normal;line-height:20px;">Problem Author: Sergey Pupyrev</span> 
</p>
<p>
Problem Source: The XIIth USU Programing Championship, October 6, 2007
</p>
<p>
<a href="http://acm.timus.ru/problem.aspx?num=1569" target="_blank">URAL 1569 Networking the “Iset”</a> 
</p>
