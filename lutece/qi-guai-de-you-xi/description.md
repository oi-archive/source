
# Content

`Blinker`最近喜欢上一个奇怪的游戏。

这个游戏在一个$N\times M$的棋盘上玩,每个格子有一个数。每次`Blinker`会选择两个相邻的格子，并使这两个数都加上$1$。

现在`Blinker`想知道最少多少次能使棋盘上的数都变成同一个数，如果永远不能变成同一个数则输出$-1$。

# Standard Input

输入的第一行是一个整数$T$，表示输入数据有$T$轮游戏组成。
 
每轮游戏的第一行有两个整数$N$和$M$，分别代表棋盘的行数和列数。
 
接下来有$N$行，每行$M$个数。

$T\leq 10$,$1\leq N$,$M\leq 40$，所有数为正整数且小于$1000000000$。 

# Standard Output

对于每个游戏输出最少能使游戏结束的次数，如果永远不能变成同一个数则输出$-1$。

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
2 2 
1 2 
2 3 
3 3 
1 2 3 
2 3 4 
4 3 2</td><td>2 
-1</td></tr></table>


# Constraints



# Note



# Source


