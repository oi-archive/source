
# Content

有一个含 $n$ 项的数列 $A_1$ 、$A_2$ 、... 、$A_n$ 。

虽然不知道每一项的具体值，但我们知道每一项的值要么为 $0$，要么为 $1$ 。

而且我们可以花 $C_{i,j}$ 的费用询问数列中第 $i$ 项到第 $j$ 项的异或和。

第 $i$ 项到第 $j$ 项的异或和为 $A_i$ ⊕ $A_{i+1}$ ⊕ ... ⊕ $A_j$ 。

其中 $0$ ⊕ $0$ = $0$ 、$0$ ⊕ $1$ = $1$ 、$1$ ⊕ $0$ = $1$ 、$1$ ⊕ $1$ = $0$ 。

那么我们至少要花多少费用才能知道数列中每一项的具体值呢？

# Standard Input

第一行一个整数 $n$，表示数列的项数。

接下来 $n$ 行中，第 $i$ 行有 $n+1-i$ 个整数，即 $C_{i,i}$ 、$C_{i,i+1}$ 、... 、$C_{i,n}$ 。

$1 \leq n \leq 1000$，$1 \leq C_{i,j} \leq 1000000$ 。

# Standard Output

输出一个整数，即要花的最小费用。

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
1 2
2</td><td>3</td></tr><tr><td>3
1 2 3
2 1
3</td><td>4</td></tr></table>


# Constraints



# Note



# Source


