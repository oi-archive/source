
# Content

给出长度为$n$的数字串，请求出其中能被$k$整除的子串个数。

# Standard Input

第一行有$2$个正整数$n$，$k$，含义如题目所示。

第二行为一个长度为$n$的仅由$0\sim 9$组成的字符串。

# Standard Output

输出一个整数表示能被$k$整除的子串个数。

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
12674</td><td>4</td></tr></table>


# Constraints

n*k&le;2e7

# Note

样例解释：

共有四个合法的串$12,126,267,6$。

虽然$24,27,174$也能被$3$整除，但在原串中的位置不连续，所以不合法。

有前导零的数字串也合法

# Source


