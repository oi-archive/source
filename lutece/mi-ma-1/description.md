
# Content

$Pxt$每过一段时间都会更换各个社交账号的密码。密码当然不能明文存储，$Pxt$随意写下了若干个$n$位16进制整数，一则$k$位的密码是将该数保留$k$位且相对位置不变的最大16进制数。

$Pxt$现在要去睡午觉，请你帮助他完成密码生成器。

# Standard Input

包含多组测试数据。

每组测试数据，第一行是两个整数$n,k$，含义如题目所示。

第二行包含一个$n$位16进制整数，字母小写，n位数以空格分隔。

# Standard Output

每组数据输出一行表示$Pxt$的$k$位密码。(不含空格)

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
<tr><td>4 2
9 a b c
6 3
1 a 2 b 3 c</td><td>bc
b3c</td></tr></table>


# Constraints

$n,k≤100,000$

# Note

数据加强，注意数据范围
存在k=0

# Source


