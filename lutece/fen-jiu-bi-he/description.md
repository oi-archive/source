
# Content

“话说天下大势，分久必合，合久必分。”

话说不只是天下大事，你看就连机械时钟的时针和分针，一天之中不也是分久必合吗？比如每天的 `00:00` 和 `12:00`，时钟的时针和分针就是重合的，当然不只这两个时刻了，其实一天之中有 $22$ 个时刻时针和分针都会重合的。

现在问题是如果给你一个起始时刻和一个终止时刻，你能计算出这中间时针和分针会重合几次吗？

# Standard Input

第一行是一个正整数 $T$，代表有 $T$ 组测试数据；

接下来是 $T$ 行输入，每行输入$4$个整数 $h\_1$ $m\_1$ $h\_2$ $m\_2$，分别代表起始时刻和终止时刻的小时数和分钟数。其中 $0\leq h\_1, h\_2 \leq 23$, $0 \leq m\_1, m\_2 \leq 59$，保证起始时刻小于终止时刻且起始时刻和终止时刻时针分针都不重合。

# Standard Output

对于每行输入，输出相应的一行结果，即从起始时刻到终止时刻时针和分针一共会相遇几次。

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
<tr><td>6
12 50 13 02
03 08 03 20
02 45 11 00
11 00 15 20
01 02 12 50
03 20 15 08</td><td>0
1
8
4
11
10</td></tr></table>


# Constraints



# Note



# Source


