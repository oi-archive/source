
# Content

给定 $n$ 这个正整数，计算下式的值

$$
\sum_{i=1}^{n}\sum_{j=1}^{n}ij\varphi(\gcd(i,j))
$$

$\gcd(i,j)$ 表示 $i$ 与 $j$ 的最大公约数。

$\varphi(x)$ 表示 $1$ 到 $x$ 中与 $x$ 互质的数的个数，即 $\varphi(n)=\sum_{i=1}^{n}[\gcd(i,n)=1]$。

# Standard Input

第一行有一个正整数 $t\ (1\le t \le 5000)$。

下面有 $t$ 组测试用例，每个测试用例包含一个正整数 $n\ (1\le n\le 10^7)$。

# Standard Output

对于每个测试用例，输出一个整数表示该式子对 $10^9+7$ 的取模后的值。

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
<tr><td>3
1
2
3</td><td>1
9
45</td></tr></table>


# Constraints



# Note



# Source


