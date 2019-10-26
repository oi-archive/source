
# Content

任意输入一个只含`+-*/`的算术表达式，没有括号，求该表达式的值。其中参与运算的数都是非负整数，范围为$[1,500]$。整个式子至少包含一个运算符，至多有$30$个运算符。要求除法按整数除法。题目保证中间运算和最后的运算结果不超过整数的存储范围。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 50$），表示测试数据的组数。每一组测试数据只有一行，为一个简单的四则运算表达式。该行没有其它多余的符号。

# Standard Output

对应每组输入，输出该表达式的运算结果，占一行。该行不能有其它多余的符号。

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
5/2
1*2+3-5
2+4*3/2+3-5</td><td>2
0
6</td></tr></table>


# Constraints



# Note

表达式中的数据没有多余的前导$0$

# Source


