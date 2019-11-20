
# Content

设 $\mathrm{xem}$ 表示集合中最小的未出现的正整数，
如 $\mathrm{xem}\{\} = 1$，$\mathrm{xem}\{1,3,4\} = 2$.

定义

$b_i = \mathrm{xem}\{b_{i-c_i}, b_{i-c_i+1}, ..., b_{i-1}\}, \quad i = 1, 2, ..., n$

特别的，$b_0 = 1$.

给定 $n$ 和 $c_1, c_2, ..., c_n$，请你计算出
$b_1, b_2, ..., b_n$.

# Standard Input

第一行一个整数 $n\ (1 \le n \le 10^6)$.

第二行 $n$ 个用空格分隔的整数 $c_1, c_2, ..., c_n$，
保证 $1 \le c_i \le i$.

# Standard Output

输出一行 $n$ 个用空格分隔的整数，
依次为 $b_1, b_2, ..., b_n$.

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
<tr><td>6
1 2 3 1 3 4</td><td>2 3 4 1 2 5</td></tr></table>


# Constraints



# Note



# Source


