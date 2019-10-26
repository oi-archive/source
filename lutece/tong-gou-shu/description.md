
# Content

写一个函数，判断所给出的数是否是同构数(若一个数出现在自己的平方数的右边就称为同构数，例如：$5$的平方数是$25$，且$5$出现在$25$的右边，$5$是同构数；又如$25$出现在$625$的右边，也是同构数)。程序要求不能用全局变量。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 70000$），表示测试数据的组数。每一组测试数据只包含整数$n$，占一行。该行没有其它多余的符号。$10\le n<10^9$。

# Standard Output

要求首先输出$1\sim 32767$中所有的同构数（从小到大），占一行，每个数后恰有一个空格。

对应每组输入，输出一行结果，如果对应数是同构数，则输出`Yes`，否则输出`No`。该行不能有其它多余的符号。

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
76
80586385</td><td>1 5 6 25 76 376 625 9376 
Yes
No</td></tr></table>


# Constraints



# Note

如果数据过大，可以考虑`long long`数据类型。

# Source


