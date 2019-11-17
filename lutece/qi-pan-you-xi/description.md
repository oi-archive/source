
# Content

最近昀昀学习到了一种新的棋盘游戏，这是一个在一个$N\times N$的格子棋盘上去搞$M$个棋子的游戏，游戏的规则有下列几条：
1. 棋盘上有且仅有一个出口
2. 开始时没有哪个棋子在出口，而且所有棋子都不相邻（这里的相邻是指上下左右四个方向）
3. $M$个棋子分别记为$1$到$M$
4. 每个时刻你可以移动一个棋子向它相邻的四个格子移动一步
5. 你需要保证任意时刻棋盘上所有棋子都不相邻
6. 只有当前棋盘上编号最小的棋子移动到出口时才能取走改棋子。
7. 所有棋子都移走的时候游戏结束

对于一个给定的游戏局面，昀昀最少要多少步才能结束这个游戏呢？

# Standard Input

第一行有一个整数$T$，($T\leq 200$)，表示测试数据的组数。

对于每一组数据，第一行是两个整数$N,M$，其中$2\leq N\leq 6$, $1\leq M\leq 4$。

接下来是一个$N\times N$的棋盘，其中`o`代表空格子，`x`代表出口,其余的$1$到$M$代表这$M$个棋子。

保证数据是合法的。

# Standard Output

对于每一组数据输出最少步数，如果无解输出$-1$。

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
<tr><td>2
3 2
x2o
ooo
oo1

3 3
xo1
o2o
3oo</td><td>7
-1</td></tr></table>


# Constraints



# Note



# Source


