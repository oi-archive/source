
# Content

$24$点就是给你一串数字，问你是否通过加减乘除括号构成$24$点。

沈爷觉得这个很好玩，就决定考考你，给你$4$个数，可以交换位置，可以用加减乘除和括号，是否能构成$24$点呢？

注意哦~这里的除法并不是整数除法，比如样例

# Standard Input

第一行$T$，表示有多少组测试数据，$1 \leq T \leq 50$

接下来$T$行，每行$4$个正整数$a_1$, $a_2$, $a_3$, $a_4$，表示每个数都是多少，$1 \leq a _i \leq 13$

# Standard Output

对于每一次询问，如果能够凑成$24$点，输出`yes`，否则输出`no`

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
3 3 8 8
1 1 1 1</td><td>yes
no</td></tr></table>


# Constraints



# Note

$3$ $3$ $8$ $8$

就可以构造出 $8 \div (3 – 8 \div 3)=24$

# Source


