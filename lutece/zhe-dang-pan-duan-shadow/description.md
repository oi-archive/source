
# Content

在一个广场上有一排沿着东西方向排列的石柱子，阳光从东边以一定的倾角射来（平行光）。有的柱子可能被在他东边的高大的柱子的影子给完全遮挡住了。现在你要解决的问题是求出有多少柱子是没有被完全遮挡住的。

假设每个石柱子是一根细棒，而且都垂直于地面摆放。

# Standard Input

输入包含多组数据。每组数据第一行是一个整数$N$($0<N \leq100000$)，表示柱子的个数。$N=0$代表输入结束。

接下来有$N$行，每行是两个整数，分别给出每根柱子的水平位置$X$和高度$H$（$X$越大，表示越在西边，$0 \leq X \leq 10000000,0 < H \leq 10000000$，保证不会有两根柱子在同一个$X$坐标上）。

最后有一行，以分数的形式给出太阳光与地面的夹角的正切值$T/A$($1 \leq A,T \leq 10$)。

# Standard Output

对每组数据，输出包含所求数目的一行。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>4
0 3
3 1
2 2
1 1
1/1
0</td><td>2</td></tr></table>


# Constraints



# Note

输入数据很多，请用`scanf`代替`cin`。

# Source


