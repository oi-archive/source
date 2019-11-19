
# Content

给一个数字串$s$和正整数$d$, 统计$s$有多少种不同的排列能被$d$整除（可以有前导$0$）。例如$123434$有$90$种排列能被$2$整除，其中末位为$2$的有$30$种，末位为$4$的有$60$种。

# Standard Input

输入第一行是一个整数$T$，表示测试数据的个数，以下每行一组$s$和$d$，中间用空格隔开。$s$保证只包含数字$0, 1, 2, 3, 4, 5, 6, 7, 8, 9$.
|s| <= 11 , d <= 1000

# Standard Output

每个数据仅一行，表示能被$d$整除的排列的个数。

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
<tr><td>7
000 1
001 1
1234567890 1
123434 2
1234 7
12345 17
12345678 29</td><td>1
3
3628800
90
3
6
1398</td></tr></table>


# Constraints



# Note



# Source


