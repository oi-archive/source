
# Content

魔法少女小糖喜欢用魔法来旅游。

现在有 $n$ 个小岛，小糖最开始在 $1$ 号小岛。他可以使用 $m$ 种魔法，每种魔法有五个参数 $l_1,r_1,l_2,r_2,w$，表示如果他使用这种魔法，且他当前所在的点 $u$ 满足 $l_1 \le u \le r_1$，那么他可以选择一个点 $v$ 满足 $l_2 \le v \le r_2$，然后消耗 $w$ 点魔法值移动到 $v$。每种魔法使用次数不限。

小糖想知道，如果他想去到某个小岛，他最少要消耗多少魔法值。

# Standard Input

第一行两个整数 $n$ 和 $m$ ($1 \le n,m \le 10^5$)，表示小岛个数与魔法种数。

接下来 $m$ 行，每行五个整数 $l_1,r_1,l_2,r_2,w$ ($1 \le l_1,r_1,l_2,r_2 \le n, l_1 \le r_1, l_2 \le r_2, 1 \le w \le 10^9$)，表示一种魔法，含义见题目描述。

# Standard Output

一行 $n$ 个数，第 $i$ 个数表示从 $1$ 号小岛出发去往 $i$ 号小岛最少消耗多少魔法值。如果无法到达该小岛，输出 $-1$。

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
<tr><td>6 2
1 3 1 3 2
2 3 5 6 1</td><td>0 2 2 -1 3 3</td></tr></table>


# Constraints



# Note



# Source


