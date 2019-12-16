
# Content

输入矩阵的阶数$n$，然后按以下规律生成二维$n$行$n$列的矩阵：$A$中第$1$行元素为$1, 2, \cdots , n$; 第$2$行元素为$n+1, n+2, \cdots , 2n$; 第$3$行元素为$2n+1, 2n+2, \cdots , 3n$; $\cdots$ 。计算：(1) $A$中所有不靠边元素之和；(2) $A$中两条对角线元素之和。

要求模拟出矩阵，按上述要求直接计算。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 100$），表示测试数据的组数。每一组测试数据只有一个整数$n$，占一行。该行没有其它多余的符号。$0<n\le 1000$。

# Standard Output

对应每组输入，输出三个数，分别为不靠边元素之和、主对角线元素之和与副对角元素之和，相邻两数之间有一个空格。该行不能有其它多余的符号。

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
3</td><td>5 15 15</td></tr></table>


# Constraints



# Note

数较大，可以考虑用`long long`数据类型，对应的输出格式串为`%lld`。

# Source


