
# Content

王被困在了一个$3$维的迷宫中，他很想逃离这个迷宫回去当学霸，你能帮助他么? 由于王很仁慈，他悄悄地告诉你，本题读入迷宫的每一行时，要用`scanf("%s"...)` ......

# Standard Input

多组测试数据，对于每组测试数据，有三个整数 $L$,$R$,$C$（$0 < l , r , c\leq 30$）。

$L$代表迷宫的高度，$R$和$C$分别代表每一层的行和列。

接下来是$L$个$R\times C$的矩阵，矩阵包含$4$种字符（`S`,`E`,`.`,`#`）,`S`代表王的初始位置，`E`代表出口，`#`代表障碍。`.`代表能通过的地方。

每一层之后有一个空行。

当$L=R=C=0$时，输入中断。

# Standard Output

如果可以逃离迷宫，按下列格式输出最短时间：

`Escaped in x minute(s). ` ($x$表示逃离迷宫的最短时间, 走一步花费一昏钟)

否则，输出:

`Trapped!`

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
<tr><td>3 4 5
S....
.###.
.##..
###.#

#####
#####
##.##
##...

#####
#####
#.###
####E

1 3 3
S##
#E#
###

0 0 0</td><td>Escaped in 11 minute(s).
Trapped!</td></tr></table>


# Constraints



# Note



# Source


