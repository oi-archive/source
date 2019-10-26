
# Content

Xie是一个很无聊的人，他最喜欢的事就是随手拿一些可怕的东西来玩。

现在，xie在$x$轴上放了$n$个地雷。第一个地雷的坐标是$x\_1$，第二个的坐标是$x\_2$,..,第$n$个的坐标是$x\_n$。

现在xie有$m$个关于这些地雷的询问，每个询问分为以下两类：
1. 把第$p\_j$个地雷从所在的位置$x\_{p\_j}$移动到$x\_{p\_j}+d\_j$。数据保证，每次移动之后，每个地雷的坐标都不同。
2. 为了评估地雷爆炸的威力，计算线段$[l\_j,r\_j]$上的每对地雷的距离之和。也就是说，要计算$\sum\_{l\_j\leq x\_p\leq x\_q\leq r\_j}(x\_q-x\_p)$

# Standard Input

第一行一个整数$T$，表示数据组数。

每组数据第一行一个整数$n$($1\leq n\leq 10^5$)，地雷的数量。第二行包含$n$个不同的整数$x\_1,x\_2,\cdots ,x\_n$，表示地雷的坐标。

第三行有一个整数$m$，代表询问的数量($1\leq m\leq 10^5$).接下来$m$行描述这些询问。第j行的第一个整数$t\_j$($1\leq t\_j\leq 2$)，表示询问的类型。如果$t\_j=1$,那么接下来会有两个整数$p\_j$和$d\_j$($1\leq p\_j\leq n$,$|d\_j|\leq 1000$)。如果$t\_j=2$，那么会有两个整数$l\_j,r\_j$($-10^9 < l\_j \leq rj \leq 10^9$)

保证任意时刻，所有的地雷都在不同的坐标上。

# Standard Output

对于每个第2类型的询问，输出一行答案。输出答案请按询问出现的顺序来输出。

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
<tr><td>1
8
36 50 28 -75 40 -60 -95 -48
20
2 -61 29
1 5 -53
1 1 429
1 5 130
2 -101 -71
2 -69 53
1 1 404
1 5 518
2 -101 53
2 50 872
1 1 -207
2 -99 -40
1 7 -389
1 6 -171
1 2 464
1 7 -707
1 1 -730
1 1 560
2 635 644
1 7 -677</td><td>176
20
406
1046
1638
156
0</td></tr></table>


# Constraints



# Note

地雷放好之后，建议不要移动，会爆炸。

# Source


