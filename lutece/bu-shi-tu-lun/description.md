
# Content

给出一个$n$个点，$m$条边的有向图。每个点上有分值，经过这个点时可以获得一定的分数。

一个点可以经过多次，但是一个点上的分数只能获得一次。

问最多能获得多少分数，起点任选。

1<=$n$<=30000,1<=$m$<=100000

# Standard Input

输入包含多组数据

每组数据第一行为$n$，$m$

接下来$n$行，每行有一个数，表示第$i$个节点的分值。

接下来$m$行，每行有两个数$a$、$b$，表示有一条从$a$到$b$的有向边

# Standard Output

每组数据输出一行，每行仅有一个整数：可以获得的最多的分数。

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
<tr><td>5 5
1 1 1 2 3
1 2
2 3
3 1
1 4
1 5
5 3
1 2 3 4 5
1 2
1 3
4 5</td><td>6
9
</td></tr></table>


# Constraints



# Note



# Source


