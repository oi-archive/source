
# Content

总所周知，韬哥哥是一只欧洲海豹。某天，韬哥哥的X日之都开了新池子，于是他决定继续白嫖。这个池子一共有$n$个不同的S(稀有度)，韬哥哥只会抽一轮，这一轮只会抽出恰好$d$个S，而且$d$一定是$n$的一个因子，这$d$个S也不会重复。这$d$个S可能有很多种组合方案，对于所有可能的$d$，这些方案数加起来就是韬哥哥这次抽卡的白嫖指数$k$。如果这次抽卡花费了$m$个石头，那么韬哥哥这次抽卡的白嫖值就是$m^k$。因为韬哥哥是个数学天才，所以他想让不会数学的jj计算一下这次抽卡的白嫖值，由于白嫖值可能很大，韬哥哥会给一个质数$p$，jj只需要回答白嫖值模$p$后的答案。韬哥哥保证​$\mu(p-1)$不为0(​$\mu$为莫比乌斯函数)。但是jj太笨了，想要请你来帮他回答。

# Standard Input

一行三个整数$n,m,p$

# Standard Output

一行一个整数，表示模$p$后的答案

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
<tr><td>4 2 10007</td><td>2048</td></tr></table>


# Constraints

$1 \le n \le 10^9$

$1 \le m \le 10^9$

$p$为质数且$p \lt 10^6$

# Note



# Source


