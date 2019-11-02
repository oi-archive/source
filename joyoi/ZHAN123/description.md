# 题目描述：
给定一个只包含加法和乘法的算术表达式，请你编程计算表达式的值。
# 输入格式：
输入仅有一行，为需要你计算的表达式，表达式中只包含数字、加法运算符“+”和乘法运算符“*”，且没有括号，所有参与运算的数字均为0到2^31-1之间的整数。输入数据保证这一行只有0~9、+、*这12种字符。
# 输出格式：
输出只有一个行，包含一个整数，表示这个表达式的值。注意：当答案长度多于4位时，请只输出最后4位，前导0不输出。
![](/source/joyoi/ZHAN123/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL1pIQU4xMjMvaHR0cHM6Ly9jZG4ubHVvZ3Uub3JnL3VwbG9hZC9waWMvNDQ4MzMucG5n.png)
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>1+1234567890*1</td><td>7891</td></tr><tr><td>1+1*3+4</td><td>8</td></tr><tr><td>1+1000000003*1</td><td>4</td></tr></table>
