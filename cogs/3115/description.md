# 题目描述


<h3>
【题目描述】
</h3>
<p>
一张 n 个点 m 条边的有向图，点从 0 到 n-1 编号，每条边有权值 t[i]。你需要选择一些边，使得任意从 0 到 n-1 的路径都经过了恰好一次你选择的边，并最小化选择的边的权值和。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个整数 n,m，表示点数和边数。
</p>
<p>
接下来 m 行，每行三个整数 u[i],v[i],t[i]，描述一条从 u[i]到 v[i]，权值为 t[i]的有向边。
</p>
<h3>
【输出格式】
</h3>
<p>
如果不存在方案，则输出-1；否则输出最小的权值和。
</p>
<h3>
【样例输入】
</h3>
<pre>6 7
0 1 5
0 2 5
1 3 1
2 4 1
4 1 1
3 5 5
4 5 5
</pre>
<h3>
【样例输出】
</h3>
<pre>6
</pre>
<h3>
【提示】
</h3>
<p>
对于 30%的数据，m≤15
</p>
<p>
对于 50%的数据，n≤15
</p>
<p>
对于 100%的数据，2≤n≤100,m≤2500,1≤t[i]≤10^9
</p>
<p>
保证存在至少一条从 0 到 n-1 的路径。
</p>