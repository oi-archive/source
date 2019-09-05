# 题目描述


<h3>
【题目描述】
</h3>
<p>
现在有N个点M条有向边组成能源网络图。每一个结点有一个初始值Ai，表示第i个结点可以提供的额外能源供给。
</p>
<p>
如果结点x到结点y有一条有向边，那么就意味着结点x的需要结点y传输能源。结点x会挑选由它出发的边的终点中，权值最大的点（假设为y）作为能源供给点，花费的代价就是Ay： Wx=max{Ay}  Ay必须满足x到y存在一条有向边。
</p>
<p>
也就是说补充能源x结点的花费为x结点连接的所有终点y中Ay的最大值。
</p>
<p>
当然，作为能源提供者的某些点，还可以选择花费额外的Bi的花费将此结点的Ai清为0。
</p>
<p>
而你现在就要计算一下这个能源网络图所有传输能源的最小花费。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个整数N和M
</p>
<p>
第二行N个整数，A1,A2……AN
</p>
<p>
第三行N个整数，B1,B2……BN
</p>
<p>
接下来M行，每行两个整数xj和yj，表示存在xj到yj的一条有向边。
</p>
<h3>
【输出格式】
</h3>
<p>
一个整数，保证这个能源网络图正常运营的最小花费。
</p>
<h3>
【样例输入】
</h3>
<p>
</p><p>
2 1
</p>
<p>
100000 10000
</p>
<p>
100000 1
</p>
<p>
1 2
</p>
<p></p>
<h3>
【样例输出】
</h3>
<p>
1
</p>
<h3>
【提示】
</h3>
<p>
最优方案是花费1的费用将A2改为0。
</p>
<p>
【数据范围】
</p>
<p>
 30%     N&lt;=20
</p>
<p>
 100%    1&lt;=N&lt;=1000  0&lt;=M&lt;=50000  0&lt;=Ai&lt;50000  0&lt;=Bi&lt;=10000
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>