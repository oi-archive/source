
# Content

oy十分喜欢一种序列,为此他特意命名这种序列为oy序列
oy序列的定义如下:oy序列是一个长度为$2*k+1(k=0,1,2\cdots)$的序列,其中前$k+1$个数字严格递增,后$k+1$个数字严格递减
例如 $1,2,3,4,5,4,3,2,1$就是一个长度为9的oy序列
现在你有一个长度为$n$的序列$a$,你需要在a的子序列中找出最长的oy序列.

# Standard Input

第一行一个数字$n$,代表序列$a$的长度
第二行依次给出$a_1,a_2,a_3,\cdots,a_{n-1},a_n$

# Standard Output

oy只关心oy序列的长度,所以你只需要输出最长的oy序列的长度

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
<tr><td>20
15 5 8 18 4 18 14 2 14 9 10 16 14 7 1 18 18 4 10 3</td><td>9</td></tr></table>


# Constraints

$1 \leq n \leq 10^6$

$-10^9 \leq ai \leq 10^9$

# Note



# Source


