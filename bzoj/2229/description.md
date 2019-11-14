
# Description

<div class="content"><p>小白在图论课上学到了一个新的概念——最小割，下课后小白在笔记本上写下了如下这段话： “对于一个图，某个对图中结点的划分将图中所有结点分成两个部分，如果结点s,t不在同一个部分中，则称这个划分是关于s,t的割。 对于带权图来说，将所有顶点处在不同部分的边的权值相加所得到的值定义为这个割的容量，而s,t的最小割指的是在关于s,t的割中容量最小的割” 现给定一张无向图，小白有若干个形如“图中有多少对点它们的最小割的容量不超过x呢”的疑问，小蓝虽然很想回答这些问题，但小蓝最近忙着挖木块，于是作为仍然是小蓝的好友，你又有任务了。</p></div>

# Input

<div class="content"><p>输入文件第一行有且只有一个正整数T，表示测试数据的组数。 对于每组测试数据， 第一行包含两个整数n,m，表示图的点数和边数。 下面m行，每行3个正整数u,v,c(1&lt;=u,v&lt;=n,0&lt;=c&lt;=106)，表示有一条权为c的无向边(u,v) 接下来一行，包含一个整数q，表示询问的个数 下面q行，每行一个整数x，其含义同题目描述。</p></div>

# Output

<div class="content"><p>对于每组测试数据，输出应包括q行，第i行表示第i个问题的答案。对于点对(p,q)和(q,p)，只统计一次（见样例）。</p>
<p>两组测试数据之间用空行隔开。</p></div>

# Sample Input

<div class="content"><span class="sampledata">      1<br/>
     5 0<br/>
     1<br/>
     0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
<br/>
【数据范围】<br/>
对于100%的数据  T&lt;=10,n&lt;=150,m&lt;=3000,q&lt;=30，x在32位有符号整数类型范围内。<br/>
    图中两个点之间可能有多条边<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

