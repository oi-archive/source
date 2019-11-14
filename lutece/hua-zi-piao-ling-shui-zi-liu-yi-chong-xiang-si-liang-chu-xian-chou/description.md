
# Content

在一座城市中，有 $n$ 个地区，地区之间由 $m$ 条单行道连接。

某游客由机场出发，通过这些单行道游览城市，**最后回到机场**。

由于游客可能不熟悉道路，该城市的法律能够容忍游客在单行道上逆行一次。

现在该游客想知道他最多能游历多少个不同的地区。

# Standard Input

第一行两个整数 $n$ 和 $m$，表示地区和单行道的数量。

接下来 $m$ 行每行两个整数 $x$ 和 $y$，表示有一条 $x$ 到 $y$ 的单行道。

地区由 $1$ 到 $n$ 进行编号，且**机场位于 $1$ 号地区**。

$1 \leq n$ 、$m \leq 100000$，$1 \leq x$ 、$y \leq n$ 。

# Standard Output

输出一个整数，即最多逆行一次的情况下游历的地区数的最大值。

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
1 2
2 3
3 1</td><td>3</td></tr><tr><td>3 3
1 2
2 3
1 3</td><td>3</td></tr></table>


# Constraints



# Note



# Source


