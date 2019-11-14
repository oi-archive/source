
# Content

小明最近学习了数据结构的课程。小明非常喜欢树这种结构。于是小明构造了一棵树，并且在他构造的这棵树上玩了一个小游戏。

我们定义这棵树上节点的度数等于与它相连的节点的个数。小明构造的树是这样的，有$n$个点，除了节点1的度数有可能大于$2$外，其他所有的节点的度数最多只有$2$。

开始的时候，这棵树的每个节点上的权值都为$0$。小明的这个小游戏有两个操作。

第一个操作`0 v x d`，表示小明给所有与节点v距离不超过$d$的节点权值加上$x$，两个节点之间的距离等于两个节点之间的最短路上的边的数目（有可能跨越过根节点到达与根节点相连的其他子树）。

第二个操作`1 v`，表示小明输出节点$v$的权值。

# Standard Input

有多组数据，每组数据首先是两个数字$n$($2\leq n\leq 10^5$)，$q$($1\leq q\leq 10^5$),分别表示这棵树上有多少个节点，有多少个操作。然后下面是$n-1$行，每行有两个数字$u$和$v$($1\leq u\_i,v\_i\leq n$,$u\_i\neq v\_i$)，表示$u$和$v$之间有一条边相连。保证每条边只出现一次，并且保证给出的树满足题目描述的要求。

然后接下来有$q$行：
* `0 v x d`,表示第一个操作($1\leq v\leq n$,$1\leq x\leq 10^4$,$1\leq d < n$)
* `1 v`，表示第二个操作 ($1\leq v\leq n$)

# Standard Output

对于要输出节点权值的操作（即第二个操作），输出一个整数。

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
<tr><td>3 6
1 2
1 3
0 3 1 2
0 2 3 1
0 1 5 2
1 1
1 2
1 3
6 11
1 2
2 5
5 4
1 6
1 3
0 3 1 3
0 3 4 5
0 2 1 4
0 1 5 5
0 4 6 2
1 1
1 2
1 3
1 4
1 5
1 6</td><td>9
9
6
11
17
11
16
17
11</td></tr></table>


# Constraints



# Note



# Source


