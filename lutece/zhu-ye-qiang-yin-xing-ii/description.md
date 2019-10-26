
# Content

若干年后，柱爷再次来到了喵哈哈城，准备再干一票！！

这一次，喵哈哈城早已不是之前的样子，而是一个由$N$个格子组成的环，格子编号为$1..N$，按顺时针排列。第$1$个格子和第$N$个格子是相邻的。

每个格子都有一家银行，抢第$i$个银行的收益是$a\_i$。柱爷也可能遇上陷阱，所以收益可以是负数。

柱爷决定从这些银行中选择一个区间，沿顺时针抢劫这个区间内的所有银行！但为了不被抓到，柱爷最多只能抢$K$个银行。

当然，柱爷既然下定决心了，就至少得抢一家银行。

请你帮柱爷选一个区间，让柱爷抢到最多的钱。

# Standard Input

第一行两个整数$N$，$K$。

第二行有$N$个整数$a\_{i}$，表示抢劫第$i$家银行的收益。

数据保证：

* $1 \leq K \leq N \leq 1 000 000$

* $-1000 \leq a\_i \leq 1000$

# Standard Output

输出一行三个数$x，l， r$，用空格隔开。

分别表示柱爷最多能抢到的钱，最开始的银行编号，最后的银行编号。如果答案不唯一，输出开始编号最小的。如果还不唯一，输出区间长度最短的。

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
<tr><td>6 3
6 -1 2 -6 5 -5
</td><td>7 1 3
</td></tr><tr><td>6 6
-1 -1 -1 -1 -1 -1
</td><td>-1 1 1
</td></tr></table>


# Constraints



# Note



# Source


