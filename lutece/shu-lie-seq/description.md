
# Content

给出一个长度为n的数列A。现有如下两种操作：

修改操作：把数列中第i个数改为x

询问操作：给定一个位置i，问数列中有多少个位置j ( j>i )，满足位置i与位置j间所有的数都不超过Ai与Aj的较大值。

现共有m个操作，请对每个询问操作做出回答。

# Standard Input

第一行两个正整数n、m。

随后n行，每行一个正整数Ai。

随后m行，若是修改操作，则以一个大写C开头，随后两个正整数i和x；若是查询操作，则以一个大写Q开头，随后一个正整数i。

# Standard Output

每行一个整数，依次对每个询问操作给出回答。

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
<tr><td>5 3
1
3
2
3
2
Q 1
C 1 3
Q 1</td><td>2
4</td></tr></table>


# Constraints



# Note

对于40%的数据，n、m<=5000

对于100%的数据，n、m<=50000，|Ai|、x<=100000

# Source


