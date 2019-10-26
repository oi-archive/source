
# Content

相信大家都玩过贪吃蛇游戏吧。

在$n \times m$的迷宫中，有着一条长度不超过$9$的贪吃蛇，它已经将所有的食物吃光了，现在的目标是移动到出口。

它走的时候不能碰到自己的身体，也不能碰到墙壁。(如果贪吃蛇的长度$>3$并且下一步要走到自己的尾部，是合法的)

问它能不能走到出口，如果能，最少要移动几步？

# Standard Input

数据包含多组数据，请读入到文件末尾`EOF`

每组数据第一行包含两个整数$n,m(1 \leq n,m \leq 15)$代表迷宫的大小。

接下来$n$行，每行包含一个长度为$m$的字符串，来表示迷宫。

字符串中仅包含`.`、`#`、`@`、`1` ~ `9`、`.`代表空地 `#` 代表墙 数字一定是$1 \sim k$ 连续的$k$个数字，代表贪吃蛇，$1$代表它的头，$k$代表它的尾，数据保证数字$i$一定和数字$i+1$在迷宫中相邻。 `@` 代表出口。

# Standard Output

对于每组数据，先输出`Case #i: ` ,$i$为当前数据组数。

接下来一个数，代表贪吃蛇最少需要移动的步数，若无法移动出去输出`-1`

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
<tr><td>4 5
##...
..1#@
432#.
...#.
3 2
3@
2#
1#</td><td>Case #1: 4
Case #2: -1</td></tr></table>


# Constraints



# Note



# Source


