
# Content

Macaron_lin 经营着一家赛马场，他打算在这里举办一场赛马。

赛马场由 $n$ 个小场地与 $n-1$ 条路组成，小场地编号为 $1$ 到 $n$，所有的小场地是连通的。每条路双向连接着两个小场地，并有一定长度，小场地的大小忽略不计。Macaron_lin 在其中 $k$ 个小场地上树立了旗帜，比赛中，选手需要从某个小场地出发，将这 $k$ 个旗帜全部收集（不需要回到起点）。

Cjj 准备要来参加这场赛马。他想知道，如果他从 $i$ 号小场地出发，收集齐所有旗帜所需最短路程是多少。

# Standard Input

第一行包含两个整数 $n$ 和 $k$ ($1 \le k \le n \le 10^5$)，表示小场地的个数和旗帜个数。

接下来 $n-1$ 行，每行包含三个整数 $u,v,w$ ($1 \le u,v \le n, 1 \le w \le 10^6$)，表示 $u$ 号小场地和 $v$ 号小场地间有一条长度为 $w$ 的路。数据保证所有小场地连通。

接下来 $k$ 行，每行包含一个整数，表示旗帜所在的位置。数据保证这 $k$ 个数互不相同。

# Standard Output

输出 $n$ 行，第 $i$ 行表示从 $i$ 号小场地出发收集齐所有旗帜所需的最短路程。

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
<tr><td>3 3
1 2 1
2 3 4
1
2
3</td><td>5
6
5</td></tr><tr><td>5 2
1 3 1
2 3 2
4 3 3
5 1 4
5
1</td><td>4
7
5
8
4</td></tr></table>


# Constraints



# Note

对于第一组样例：
- 从 $1$ 号点出发，收集所有旗帜最短路径为 $1-2-3$。
- 从 $2$ 号点出发，收集所有旗帜最短路径为 $2-1-2-3$。
- 从 $3$ 号点出发，收集所有旗帜最短路径为 $3-2-1$。

# Source


