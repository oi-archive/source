
# Description

<div class="content">现在有n个任务需要安排。每个任务都需要一天来完成，但是不同的任务可以在同一天开工。任务和任务之间有两种限制关系：
1.	冲突关系，即两个任务不可以在同一天开工。对于有冲突的任务i和j，我们用一条无向边来表示。
2.	需求关系，即一个任务必须在另一个任务完工后才能开工（不可以同时开工）。如果i任务必须在j任务前完成，我们用一条从i到j的有向边来表示。

那么n个任务之间形成了一个n个点的混合图。现在我们简化这个问题：n个任务之间形成的是一颗混合树（即把边去方向后形成一棵树）。求最少多少天能完成所有任务。

</div>

# Input

<div class="content">若干行，每行描述一个非叶子节点。一行只有0表示输入结束。
每一行的第一个数，为被描述的节点编号。
后接若干个数，每个数表示这个节点的一个孩子。每个孩子后面可能跟着一个字母。”d”表示有向边父亲指向儿子，”u”表示有向边儿子指向父亲。没有跟字母表示一条无向边。每一行的读入以0结束。0后面不会跟字母。
保证树的节点数&lt;=200

</div>

# Output

<div class="content">仅一行一个数：最少天数。

</div>

# Sample Input

<div class="content"><span class="sampledata">1 2 3d 0<br/>
2 4d 0<br/>
3 5d 0<br/>
4 6d 0<br/>
0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
</span></div>

# Hint

<div class="content"><p><br/>
一个方案如下：<br/>
第一天：1<br/>
第二天：2 3<br/>
第三天：4 5<br/>
第四天：6<br/>
<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=HNOI省队集训Day3">HNOI省队集训Day3</a></p></div>

