
# Content

你有一个n行和n列的矩阵。定义两个单元格(a,b)(c,d)位于同一对角线当且仅当(c-a)=(d-b)

每个对角线的第一个单元将按照(n,1)(n-1,1)...(1,1)(1,2)...(1,n)的顺序排列。

您需要从每个对角线中选择一个数字。 满足所有2 * n-1个数字必须是两两不同的。

# Standard Input

第1行一个整数n

第2行到第n+1行，每行n个整数，代表这个矩阵

# Standard Output

如果不能满足条件，请输出NO，否则输出YES

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
1 1
1 1</td><td>NO
</td></tr><tr><td>2
1 2
1 3</td><td>YES</td></tr></table>


# Constraints



# Note

n<=300
1<=矩阵元素<=1e9

# Source


