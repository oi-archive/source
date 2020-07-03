
# Content

给定 $n$ 这个正整数，计算下式的值

$$
\sum_{i=l}^{r}\sum_{j=1}^{i}f(i,j)
$$

$f(i,j)$ 表示 $\frac{i}{j}$ 的小数部分。

# Standard Input

第一行有一个正整数 $t\ (1\le t \le 10^6)$。

下面有 $t$ 组测试用例，每个测试用例包含两个正整数 $l,r\ (1\le l\le r\le 10^6)$。

# Standard Output

对于每个测试用例，输出一个整数表示该式子的值。

如果答案可以表示成 $\frac{P}{Q}$ 的形式，请输出 $P\times Q^{-1}\bmod 998244353$ 的值，其中 $Q^{-1}$ 表示 $Q$ 在模 $998244353$ 意义下的乘法逆元。

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
<tr><td>1
1 3</td><td>499122177</td></tr></table>


# Constraints



# Note



# Source


