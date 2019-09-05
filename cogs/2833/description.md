# 题目描述


<h3>
【题目描述】
</h3>
<p>
考虑一个无限的黑白棋盘，在棋盘上有个直角坐标系来规定每个顶点的坐标。现在有人在棋盘上画了条
</p>
<p>
不相交的闭合折线，求在这条折线内部的黑色格子与白色格子数量。保证折线的顶点都在棋盘格子的顶
</p>
<p>
点处，且折线上的边都平行于坐标轴。规定以坐标（0,0）为左下角的边长为1的正方形是黑色。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行包含整数n(1 &lt;= n &lt;= 50000) 表示折线上的顶点数量。
</p>
<p>
接下来的n 行，每行包含两个整数，表示顶点的坐标。顶点以逆时针的顺序给出。坐标大小的绝对值不
</p>
<p>
超过10e9。
</p>
<h3>
【输出格式】
</h3>
<p>
输出两个数b 和w，表示曲线内部的黑色格子和白色格子数量。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
12
1 0
2 0
2 1
3 1
3 2
2 2
2 3
1 3
1 2
0 2
0 1
1 1
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>1 4</pre>
<h3>
【数据范围】
</h3>
<p>
对于10% 的数据，n &lt;= 4。
对于30% 的数据，n &lt;= 6。
对于60% 的数据，n &lt;= 100。
对于100% 的数据，n &lt;= 50000。
</p>
<h3>
【来源】
</h3>
<p>
qbxt 2017.10.5 t2
</p>