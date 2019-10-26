
# Content

一个数的序列$B=(b\_1 , b\_2 , \cdots , b\_S)$，当$b\_1 < b\_2 < \cdots < b\_S$ 的时候，我们称这个序列是上升的。对于给定的一个序列$A=(a\_1, a\_2, \cdots, a\_N)$，我们可以得到一些上升的子序列$(a\_{i\_1}, a\_{i\_2}, \cdots, a\_{i\_K})$，这里$1 \le i\_1 < i\_2 < \cdots <i\_K \le N$。比如，对于序列$(1, 7, 3, 5, 9, 4, 8)$，有它的一些上升子序列，如$(1, 7)$, $(3, 4, 8)$等等。这些子序列中最长的长度是$4$，比如子序列$(1, 3, 5, 8)$。

你的任务，就是对于给定的序列，求出最长最小的上升子序列。所谓最长最小的子序列，是指若有多个最长子序列时，存在一个子序列$A=(a\_{s\_1},a\_{s\_2},\cdots ,a\_{s\_k})$，对其它任意最长子序列$B=(a\_{t\_1},a\_{t\_2},\cdots ,a\_{t\_k})$，有前$i-1$个元素相等, 而$a\_{s\_i}<a\_{t\_i}$，则$A$是最长最小的上升子序列。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 100$），表示测试数据的组数。每组测试数据占一行，第一个数是序列的长度$N$ ($1 \le N \le 1000$)。紧随其后是序列中的$N$ 个整数，该行每个数后均有一个空格，这些整数的取值范围都在$0$ 到$10000$。该行没有其它多余的符号。

# Standard Output

对应每组输入，先输出最长最小的上升子序列长度，再输出最长最小的上升子序列，占一行。每个数后应有一个空格，该行不能有其它多余的符号。

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
<tr><td>1
7 1 7 3 5 9 4 8</td><td>4 1 3 4 8</td></tr></table>


# Constraints



# Note



# Source


