
# Content

银牌爷和柱神开始玩MC啦，但是怪物实在是太多了，于是银牌爷决定去挖点钻石提升装备。

来到矿脉的银牌爷发现矿脉错综复杂。

矿脉是由一些矿洞和一些通道组成的，通道连着不同的矿洞。

矿洞的编号从$1$到$n$

聪明的银牌爷定义了矿脉的复杂度为下面的式子：

$\sum\_{i=1}^n\sum\_{j=1}^n\delta(i,j)^2$

其中$\delta(i,j)$表示矿洞$i$到矿洞$j$的最短路

如果最短路不存在，则为$n$

现在给出一个矿脉，银牌爷想知道这个矿脉的复杂度是多少？

# Standard Input

输入一个整数$n$,$1<=n<=2000$，表示总共$n$个矿洞，接下来$n$行$n$列，第$i$行$j$列的值$a\_{ij}=1$或者$a\_{ij}=0$，如果$a\_{ij}=1$，表示从矿洞$i$到矿洞$j$有一条长为$1$的边，如果$a\_{ij}=0$，则表示从$i$到$j$没有直接的边

# Standard Output

输出一个整数，表示矿脉的复杂度

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
010
001
100</td><td>15</td></tr><tr><td>2
10
01</td><td>8</td></tr></table>


# Constraints



# Note



# Source


