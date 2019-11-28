
# Content

给你一个$N$个点$M$条边的无向图，删掉每条边有一个花费，求把这个图分成超过一个连通块的最小花费。

# Standard Input

一组数据，第一行是$N$和$M$($2 \leq N \leq 2000$, $1 \leq M \leq 10^5$)，表示图的点数和边数。

接下来的$M$行表示图中的所有边，以`u v w`的形式给出， 表示从$u$到$v$有一条边，删掉这条边的花费是$w$，保证$u \neq v$ ($1 \leq u, v \leq N$, $1 \leq w \leq 1000$)。

# Standard Output

输出一个数，表示拆分这个图的最小花费。

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
<tr><td>2 1
1 2 102
</td><td>102
</td></tr><tr><td>5 5
1 2 5
2 4 6
1 3 7
3 4 3
5 1 10
</td><td>8
</td></tr></table>


# Constraints



# Note



# Source


