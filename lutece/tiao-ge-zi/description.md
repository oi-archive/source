
# Content

Bob喜欢玩跳格子的游戏。这天，他在地上画了一些格子，每个格子有个坐标$(x,y)$，Bob每次只能从一个格子跳到相邻的距离为$1$的格子。

Bob发现，从任意一个格子跳到另一个格子的路径有且仅有一条。现在Bob给每个格子一个分数，他想选一些格子，这些格子两两可达，并且权值和最大，你能帮他实现吗。

# Standard Input

第$1$行是一个整数$N$（$2 \leq N \leq 1000$），表示格子个数；

以下$N$行中，第$i$行($1 \leq i \leq N$)有三个整数，$X\_i$, $Y\_i$, $C\_i$依次表示第$i$个格子的横坐标，纵坐标和权。同一行相邻两数之间用一个空格分隔。$-10^6 \leq X\_i, Y\_i \leq 10^6$；$-100 \leq C\_i \leq 100$。

# Standard Output

仅一个整数，表示所选格子的权值和。

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
<tr><td>5
0 0 -2
0 1 1
1 0 1
0 -1 1
-1 0 1</td><td>2</td></tr></table>


# Constraints



# Note



# Source


