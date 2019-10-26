
# Content

二维平面给n个点（可能有重点）$P_i(1 \leq i \leq n)$，任取$i, j, k (1 \leq i < j < k \leq n)$，问有多少对$(i, j, k)$能使得$P_i, P_j, P_k$组成锐角三角形。

能组成锐角三角形的条件为：$P_i, P_j, P_k$互不相同，且三个角分别为锐角（大于0，小于90度）

# Standard Input

第一行输入一个n，表示有n个点。n最多为1000

接下来n行，每行两个整数x, y，表示每个点的坐标（绝对值不超过1e9）

# Standard Output

输出答案

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
<tr><td>5
0 0
0 0
0 0
0 2
2 1</td><td>3</td></tr><tr><td>7
11 -10
11 10
-19 -11
4 0
8 -5
2 -15
-14 7</td><td>11</td></tr></table>


# Constraints



# Note



# Source


