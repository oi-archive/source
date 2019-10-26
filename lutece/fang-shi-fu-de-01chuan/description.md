
# Content

方师傅过生日啦，于是蟹毛买了$N$个`01`串，想送给方师傅。

但是蟹毛觉得这些`01`串不够美，于是他想从中选出一些送给方师傅。

蟹毛对于$p$个`01`串的美值定义为： 这些`01`串的最长公共前缀的长度$\times p$

所以蟹毛想从$N$个`01`串中选出一些，使得这些`01`串的美值最高。

请告诉蟹毛最好的美值是多少。

# Standard Input

输入第1行包含1个整数N，表示蟹毛买到的01串的个数。

接下来N行，每行包含$1$个`01`串。

$N \leq 50000,$每个`01`串长度不超过$200$

# Standard Output

输出包含$1$个整数，代表最高的美值。

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
<tr><td>4
0000
0001
10101
010</td><td>6</td></tr><tr><td>5
01010101010100001010010010100101
01010101010100001010011010101010
00001010101010110101
0001010101011010101
00010101010101001</td><td>44</td></tr></table>


# Constraints



# Note

第一组样例，选$1,2$两个`01`串，他们的最长公共前缀为$3$，所以美值是$6$

# Source


