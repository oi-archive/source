
# Content

给定一个简单无向图，
请你判断这个图是否海星，
一个图海星当且仅当它内部存在五个互不相同的点 $A,B,C,D,E$，
满足点对$<A,C>, <A,D>,<B,D>, <B,E>, <C,E>$ 之间都存在一条边。

![](/source/lutece/wo-jue-de-hai-xing/img/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL0FicmV0by9pbWcvbWFzdGVyL2hhaXhpbmcucG5n.png)

# Standard Input

第一行包含一个正整数 $T$，表示有 $T$ 组测试数据。

接下来依次描述每组测试数据。对于每组测试数据:

第一行包含一个正整数 $n$ ，表示给定图的点数。接下来有 $n$ 行，每行有一个长度为 $n$ 的 `01` 字符串，表示给定图的邻接矩阵 $G$，$x$ 和 $y$ 之间有边相连当且仅当 $G_{xy}=1$。

数据保证 $1 \le T \le 100$ , $1 \le n \le 200$ , $G_{xx} = 0$ 以及 $G_{xy} = G_{yx}$​ ，对于 $70\%$ 的数据额外满足 $1 \le n \le 50$。

# Standard Output

对于每组测试数据输出一行，
先输出信息`"Case #x: "`，其中`x`表示这是第`x`组测试数据，
随后如果该组给出的图海星，输出`"Starfish!"`，否则输出`"Walk Walk"`。所有输出不含引号。

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
<tr><td>3
3
011
101
110
5
01111
10111
11011
11101
11110
2
00
00</td><td>Case #1: Walk Walk
Case #2: Starfish!
Case #3: Walk Walk</td></tr></table>


# Constraints



# Note



# Source


