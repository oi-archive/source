
# Content

有$n$个物品，每个物品有一个标签，标签相同的物品认为是一样的，现在要从这$n$个物品中选出r个物品，问有多少种方法。

# Standard Input

有大概$100$组数据。每组数据第一行有两个整数$n$，$m$ ($0 < n,m \leq 50$) 分别代表物品数和询问数，第二行有$n$个数，代表每个物品的标签（在$1\sim n$之间）,第三行有$m$个数，每个数代表一个询问$r$($0 \leq r \leq n$) ，$n=m=0$代表输入结束。

# Standard Output

对于每组数据，先输出一行`Case T:`，$T$为数据组数，接下来每行输出一个询问的答案。

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
<tr><td>5 2
1 1 1 2 2
1 2
5 3
1 2 3 4 5
1 2 0
0 0</td><td>Case 1:
2
3
Case 2:
5
10
1</td></tr></table>


# Constraints



# Note



# Source


