
# Content

给一棵树，如果树上的某个节点被某个人占据，则它的所有儿子都被占据，`lxh`和`pfz`初始时分别站在两个节点上，谁当前所在的点被另一个人占据，他就输了比赛，问谁能获胜。

# Standard Input

输入包含多组数据

每组第一行包含两个数$N$,$M$($N$,$M\leq 100000$)，$N$表示树的节点数，$M$表示询问数，$N=M=0$表示输入结束。节点的编号为$1$到$N$。

接下来$N-1$行，每行$2$个整数$A$,$B$($1\leq A$,$B\leq N$)，表示编号为$A$的节点是编号为$B$的节点的父亲。

接下来$M$行，每行有$2$个数，表示`lxh`和`pfz`的初始位置的编号$X$,$Y$($1\leq X$,$Y\leq N$,$X\neq Y$)，`lxh`总是先移动。

# Standard Output

对于每次询问，输出一行，输出获胜者的名字。

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
1 2
1 2
5 2
1 2
1 3
3 4
3 5
4 2
4 5
0 0</td><td>lxh
pfz
lxh</td></tr></table>


# Constraints



# Note



# Source


