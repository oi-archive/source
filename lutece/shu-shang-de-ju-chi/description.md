
# Content

给你一棵带权树，边权表示两点间的距离。有如下两种操作：
1. 询问两点间的最短距离。
2. 修改一条边权值。

对每个操作$1$，回答两点间的距离。

# Standard Input

第一行一个数$n$，表示点的个数。接下来$n-1$行，每行$3$个数$u$，$v$，$w$，表示$u$，$v$间有权为$w$的边。边按照输入顺序从$1$到$n-1$编号。输入保证为一颗树。
 （$2\leq n\leq 10^5$，$1\leq u, v\leq n$，$1\leq w\leq 1000$）

之后输入一个数$q$，表示询问个数。最后有$q$行，每行第一个数$op$（$op=1$或$2$）为操作类型。

当$op=1$时，输入$u$，$v$表示询问$u$，$v$间的距离。 （$u\neq v$，$1\leq u, v\leq n$）

当$op$为$2$时，输入$id$，$w$表示把编号为$id$的边的权值改为$w$。 
（$1\leq q\leq 10^5$，$1\leq id\leq n - 1$，$1\leq w\leq 1000$）

# Standard Output

对于对每个操作$1$，输出一行，回答两点间的距离。

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
1 2 2
2 3 3
1 5 1
2 4 4
5
1 1 3
1 2 5
2 1 1
2 3 3
1 2 5</td><td>5
3
4</td></tr></table>


# Constraints



# Note



# Source


