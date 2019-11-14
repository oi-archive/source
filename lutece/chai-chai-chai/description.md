
# Content

给你一个数x，你有两个操作

1.分解质因数，如果x是一个合数，那么就将x分解质因数，然后进入操作2，否则输出这个数

2.将分解质因数中的乘号变成加号，执行操作1

问你最后输入多少？

# Standard Input

多组数据，大概10000组，每组数据仅包含一个正整数n(1<=n<=10^9)

# Standard Output

对于每组数据，输出一个整数，表示最后的数字。如果无法得到最后的数字，输出-1

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
2
4
6
8
10</td><td>1
2
-1
5
5
7</td></tr></table>


# Constraints



# Note

1,2都不是合数

4=2^2=2*2, 2+2=4,陷入了死循环，输出-1

6=2*3,2+3=5,写出5

by qscqesze

# Source


