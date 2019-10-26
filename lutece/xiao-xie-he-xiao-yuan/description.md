
# Content

魔法少女小蟹和小圆最近喜欢上了一个游戏。

游戏是这样的：

在一个$N\times M$的棋盘上，每个格子上初始有一些棋子，两个人轮流行动，在某个人的回合里他可以选择从一个非空格子中选出大于$0$个但不大于$K$个的棋子，然后将这些棋子往右或往下移动 一格，当某一方不能移动棋子的时候就输了。

由于小蟹资历比较浅，所以她总是先手。

在两者都采取最优策略的情况下，给你棋盘初始状态，问谁必胜？

# Standard Input

第一行一个数$T$，表示$T$组$case$。

对于每组$case$，

第一行三个数，$N,M,K$，如题。

接下来$N$行每行$M$个数，

第$i$行第$j$个数$X\_{ij}$表示棋盘上$(i,j)$的位置放置的棋子数。

棋盘左上角为$(1,1)$，右下角为$(N,M)$。

($1\leq N,M\leq 50$, $1\leq K\leq 100$, $0\leq X\_{ij}\leq 100$)

# Standard Output

对于每组$case$，如果小蟹必胜，输出`XIE`，如果小圆必胜，输出`YUAN`。

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
1 3 3
1 2 3
2 2 1
1 3
1 0</td><td>XIE
YUAN</td></tr></table>


# Constraints



# Note



# Source


