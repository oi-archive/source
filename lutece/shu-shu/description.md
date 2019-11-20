
# Content

Fish是一条生活在海里的鱼，有一天他很无聊，就开始数数玩。

他数数玩的具体规则是：
1. 确定数数的进制$B$	
2. 确定一个数数的区间$[L, R]$
3. 对于$[L, R]$间的每一个数，把该数视为一个字符串，列出该字符串的每一个（连续的）子串对应的$B$进制数的值。
4. 对所有列出的数求和。

现在Fish数了一遍数，但是不确定自己的结果是否正确了。由于$[L, R]$较大，他没有多余精力去验证是否正确，你能写一个程序来帮他验证吗？

# Standard Input

输入包含三行。

第一行仅有一个数$B$，表示数数的进制。
	
第二行有$N + 1$个数，第一个数为$N$，表示数$L$在$B$进制下的长度为$N$，接下里的$N$个数从高位到低位的表示数$L$的具体每一位。
	
第三行有$M + 1$个数，第一个数为$M$，表示数$R$在$B$进制下的长度为$M$，接下里的$M$个数从高位到低位的表示数$R$的具体每一位。

$20\%$数据，$0\leq R - L\leq 10^5$。

$50\%$数据，$2\leq B\leq 1000$，$1\leq N,M\leq 1000$。

$100\%$数据，$2\leq B\leq 10^5$，$1\leq N,M\leq 10^5$。

# Standard Output

输出仅一行，即按照Fish数数规则的结果，结果用$10$进制表示，由于该数可能很大，输出该数模上$20130427$的模数。

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
<tr><td>10
3 1 0 3
3 1 0 3</td><td>120</td></tr></table>


# Constraints



# Note

$[103, 103]$之间仅有数$103$，该数的所有子串包括$1, 10, 103, 0, 03, 3$，其和为$120$。

# Source


