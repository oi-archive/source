
# Content

给两个数列A, B，长度分别为n1, n2，`保证A中每个元素互不相同，保证B中每个元素互不相同`。。进行Q次询问，每次查找A[l1...r1]和B[l2..r2]的交集 集合 大小是多少。。

比如 A = {1，2，3，4，5，6，7}，B = {7，6，5，4，3，2，1}

查询A[2..4]和B[3..5]。。A[2..4] = {2，3，4}；B[3..5] ＝ {5，4，3}，交集为{3，4}，大小为2。。

# Standard Input

第一行输入n1，第二行输入n1个数；同样，第三行输入n2，第四行输入n2个数。

第五行输入Q。。接下来Q行输入l1, r1, l2, r2。。

保证 n1, n2, Q在[$1$, $2 \times 10^5$]范围内，$1 \leq l1 \leq r1 \leq n1$，$1 \leq l2 \leq r2 \leq n2$，然后数在[$-10^9$，$10^9$]范围内。。

# Standard Output

输出Q行，表示答案。。

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
1 2 3 4 5 6 7
7
7 6 5 4 3 2 1
1
2 4 3 5</td><td>2</td></tr></table>


# Constraints



# Note

此题是hdu 5111的简化版。。完成此题后，可以去做hdu 5111

# Source


