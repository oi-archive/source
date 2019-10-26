
# Content

记一个集合的gcd为该集合内所有数的最大公约数，
求一个给定集合的非空子集的gcd的k次方的期望~

# Standard Input

第一行有一个数t,表示数据组数
接下去每组数据两行，第一行两个数n,k(0<n,k<=10^6),表示该集合有n个数字。
第二行有n个数ai(0<=ai<=2000000)代表该集合内的所有元素。

# Standard Output

每组数据输出一行，为期望乘上2^n-1,之后取模10000007的结果。

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
5 1
1 2 3 4 5
3 2
2 3 6</td><td>42
64</td></tr></table>


# Constraints



# Note

样例2中gcd为1的非空子集集有{2,3},{2,3,6}两个，
2的有{2},{2,6}两个，3的有{3},{3,6}两个，6的有{6}一个。
所以期望是(2\*1^2+2\*2^2+2\*3^2+1\*4^2)/7=64/7。

# Source


