
# Content

众所周知，在C语言中二维数组是按行存储的，所以$m$行$n$列的二维数组相当于一个$m\times n$个元素的一组数组。如果把这$m\times n$个元素看作$s$行$t$列的二维数组存储后的元素（其中，$m\times n = s\times t$），那么，原二维数组中第$i$行第$j$列的元素在新的二维数组中的行数和列数分别会是多少？假设题目中元素的行数与列数均从$0$开始计数。$1\leq m,n,s,t\leq 10000$。这儿涉及的数都是整数，不超过int类型数的范围。

# Standard Input

含多组测试数据，输入首先是一个整数$T$表示测试数据组数($0<T \leq 300$)。随后有$T$组测试数据，每组数据占一行，共有六个用一个空格隔开的整数，依次表示$m$、$n$、$s$、$t$、$i$和$j$。

# Standard Output

对应每组测试数据，输出对应的结果，两数间用一个空格隔开。

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
3 4 2 6 1 3
3 5 1 15 2 2</td><td>1 1
0 12</td></tr></table>


# Constraints



# Note



# Source


