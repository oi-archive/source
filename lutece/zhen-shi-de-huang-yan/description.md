
# Content

$N$个人做一个游戏,游戏中每个人说了一句话（可能是真的也可能是假的）

第$i$个人说：“$N$个人中有至少有$a\_i$个，至多有$b\_i$个人说的是真话！”($i = 1, 2, 3\cdots n$)你能推断出最多能有多少个人说的是真话吗？

$1\leq N\leq 100000$;

$0\leq ai\leq bi\leq 1000000000$;

# Standard Input

第一行为一个整数$T$,代表测试数据的组数；

每组数据以$n$开头，接下来有$n$行，每行两个整数$a\_i$,$b\_i$（代表第$i$个人说的）;

# Standard Output

输出占一行。如果原问题有解，输出最多能有多少个人说的是真话；否则输出`-1`.

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
<tr><td>2
3
0 0
1 1
2 2
3
2 5
3 5
0 3</td><td>1
3</td></tr></table>


# Constraints



# Note



# Source


