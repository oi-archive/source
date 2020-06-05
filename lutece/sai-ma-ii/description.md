
# Content

Macaron_lin 又要举行赛马啦！这次的比赛方式有些不同。

赛马场由 $n$ 个小场地与 $m$ 条路组成，小场地编号为 $1$ 到 $n$。每条路双向连接着两个小场地，并有一定长度，小场地的大小忽略不计。比赛中，选手需要以某个小场地为起点出发，经过若干小场地后回到起点，途中不能重复经过同一条路。

Macaron_lin 觉得这样不够刺激，于是又加入了一些新规则。比赛共分为 $k$ 轮，第一轮场上不树立旗帜。从第二轮开始，每轮比赛开始前，Macaron_lin 都会在一个没有树立旗帜的小场地上树立起一个旗帜，且这个旗帜在之后的比赛中会一直保留。每轮比赛中，选手需要以某个没有旗帜的小场地为起点出发，经过若干没有旗帜的小场地后回到起点，途中不能重复经过同一条路。

Cjj 又要来参加赛马，他想知道每轮比赛的最短路径长度。

# Standard Input

第一行三个整数 $n,m,k$ ($2 \le k \le n \le 500,1 \le m \le \frac{n(n-1)}{2}$)，表示小场地的个数、路的条数以及比赛的轮数。

接下来 $m$ 行，每行三个整数 $u,v,w$ ($1 \le u,v \le n,u \neq v,1 \le w \le 10^6$)，表示 $u$ 号小场地和 $v$ 号小场地间有一条长度为 $w$ 的路。数据保证无重边。

接下来 $k-1$ 行，每行一个整数，表示从第二轮开始每轮树立起旗帜的小场地编号。数据保证不会重复。

# Standard Output

输出 $k$ 行，第 $i$ 行表示第 $i$ 轮比赛的最短路径长度。如果没有满足条件的路径，输出 $-1$。

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
<tr><td>4 5 3
1 2 1
2 3 1
3 4 1
4 1 1
2 4 10
3
4</td><td>4
12
-1</td></tr></table>


# Constraints



# Note



# Source


