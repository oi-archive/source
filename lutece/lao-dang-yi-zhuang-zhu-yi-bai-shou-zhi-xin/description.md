
# Content

请构造一个01串，使其满足以下条件：

+ 环状（即首尾相连）
+ 每一位取值为0或1
+ 长度是$2^n$
+ 对于每个($2^n$个)位置，从其开始沿逆时针方向的连续的n位01串（包括自己）构成的数均不相同，即0到$2^n-1$中的数各出现一次

# Standard Input

输入一个整数$n(1\le n \le 15)$

# Standard Output

输出任一一个长度为$2^n$且满足题意的01串（顺逆时针均可），保证输入有解。

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
<tr><td>3</td><td>00010111</td></tr></table>


# Constraints



# Note

样例的$00010111$,对于每个位置，沿逆时针方向连续长度为3的01串有：$000, 001, 010, 101, 011, 111, 110, 100$,即为$0-7$的所有数字

# Source


