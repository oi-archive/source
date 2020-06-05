
# Content

法外狂徒张三和李四在牢里相遇了，两人发现他们都学习过图论，于是他们想比一比谁掌握得更好。

现有一张图，有 $n$ 个点与 $m$ 条无向边，点的编号为 $1$ 到 $n$，边有边权，没有重边与自环。

张三问李四：以 $x$ 号点为起点，$y$ 号点为终点，经过恰好 $k$ 条边，最短路是多长。

李四问张三：以 $x$ 号点为起点，$y$ 号点为终点，经过恰好 $k$ 条边，最短路有多少条。答案对 $1000000007$ 取模。

结果两人都互相问倒了，于是他们来请教你，你能帮帮他们吗？注意，每个点与每条边都可以经过不止一次。

# Standard Input

第一行包含四个整数 $n,m,k,o$ ($1 \le n \le 100, 0 \le m \le \frac{n(n-1)}{2}, 1\le k \le 10^9, 1 \le o \le 2$)，$o$ 的意义见输出格式。

接下来 $m$ 行，每行三个整数 $u,v,w$ ($1 \le u,v \le n, -10^6 \le w \le 10^6$)，表示 $u$ 号点和 $v$ 号点之间有一条边权为 $w$ 的无向边。数据保证没有重边与自环。

# Standard Output

输出 $n$ 行 $n$ 列。

当 $o$ 为 $1$，第 $x$ 行第 $y$ 列表示以 $x$ 号点为起点，$y$ 号点为终点，经过恰好 $k$ 条边，最短路是多长。如果最短路不存在，输出 $-1$。

当 $o$ 为 $2$，第 $x$ 行第 $y$ 列表示以 $x$ 号点为起点，$y$ 号点为终点，经过恰好 $k$ 条边，最短路有多少条。答案对 $1000000007$ 取模。如果最短路不存在，输出 $0$。

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
<tr><td>3 3 1 1
1 2 1
2 3 1
3 1 1</td><td>-1 1 1
1 -1 1
1 1 -1 </td></tr><tr><td>3 3 1 2
1 2 1
2 3 1
3 1 1</td><td>0 1 1
1 0 1
1 1 0</td></tr></table>


# Constraints



# Note



# Source


