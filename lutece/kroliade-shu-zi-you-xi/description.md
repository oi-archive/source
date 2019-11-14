
# Content

Krolia正在研究一个无聊的数字游戏。一开始有一个整数$n$，由$d$位数位构成。她每次都会选择两个相邻的数位，将其中一个加$1$，其中一个减$1$。减$1$的那个数位必须大于$0$，并且不能出现前导$0$。如果加$1$的那位是$9$，则$9$会变成两个数位，成为$10$。

现在Krolia想知道，能否通过这种变换，将数$n$变为数$m$。

# Standard Input

第一行一个整数$t$($t\leq 100$),表示测试数据的组数。

每组测试数据一行：两个整数$n,m$($0\leq m,n\leq 10^9$)。

# Standard Output

每组数据输出一个字符串：`yes`或者`no`，对应能否将$m$变成$n$。

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
<tr><td>3
10 1
92 101
110 200</td><td>no
yes
yes</td></tr></table>


# Constraints



# Note



# Source


