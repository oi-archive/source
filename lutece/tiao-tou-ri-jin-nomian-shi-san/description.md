
# Content

省府弟子乐天潭在条头日今的笔试中遇到了四道题，其中第三题是：

已知一棵 n 个结点的树，每条边都有一个边权。

现需要依次加入 m 条边，每加入一条边需要删除一条边使之仍为一棵树，同时要让这棵树的边权和最小。

当然可以删除新加入的边（相当于不加入）。

乐天潭很强势，一眼就知道了解法，但计算量实在过大，没办法只好偷偷掏出手机请你帮他写一个程序算出答案。

# Standard Input

第一行，两个整数 n (1 <= n <= 100000)，m (1 <= m <= 100000)。

接下来 n-1 行，每行三个整数 u (1<= u <= n)，v (1<= v <= n)，w (1<= w <= 100)，表示边 (u，v) 的边权为 w。

接下来 m 行，每行三个整数 u (1<= u <= n)，v (1<= v <= n)，w (1<= w <= 10000)，表示新加入一条边 (u，v) 的边权为 w。

# Standard Output

对于每次加边输出一行，表示最小边权和。

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
<tr><td>3 4
1 2 10
2 3 20
1 2 5
2 3 10
1 3 3
1 2 1</td><td>25
15
8
4</td></tr></table>


# Constraints



# Note



# Source


