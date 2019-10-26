
# Content

方老师喜欢一种字符串，包含以下两个条件：
  1. 包含且仅包含$N$个$0$和$M$个$1$
  2. 通过压缩变换之后可以得到$G$

压缩变换这样定义：如果这个字符串长度大于等于$2$，那么
  1. 如果最后两个字符是两个$0$，将这两个$0$替换为$1$ eg. `0100` -> `011`
  2. 如果最后两个字符不全是$0$，将这两个字符替换为$0$  eg. `01010` -> `0100`.

现在方老师想知道有多少满足条件的字符串。(对$1000000007$取模)

# Standard Input

三个数 $N,M$和$G$。

$N,M \leq 10^5,N+M \geq 1,0 \leq G \leq 1$

# Standard Output

一个数表示有多少个字符串(对$1000000007$取模)

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
<tr><td>2 2 0</td><td>4</td></tr></table>


# Constraints



# Note



# Source


