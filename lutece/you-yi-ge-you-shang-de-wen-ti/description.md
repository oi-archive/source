
# Content

对于一个素数$P$，如果$r$满足$r,r^2,r^3\cdots,r^{p-1}$模$P$各不相同，则称$r$是素数$P$的一个根。

现在给你一些$P$和一些$r$，请你判断$r$是否是$P$的根。

# Standard Input

多组$case$。每个$case$第一行读入两个整数$P$和$n$，$1 < P<2^{31}$,$1\leq n\leq 100$, $P$表示给定的素数，$n$表示接下来有$n$个查询。

接下来$n$行，每一行读入一个$r\_i$,请你判读$r\_i$是否是$P$的一个根,$1\leq r\_i\leq 2^{31}$;

如果输入的$P=0$，$n=0$，表示输入结束。

# Standard Output

对于每一个查询，如果$r\_i$是$P$的根，输出一个`YES`，否则输出`NO`。

在每一组样例之后输出一个空格。

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
<tr><td>5 2
3
4

7 2
3
4

0 0</td><td>YES
NO

YES
NO</td></tr></table>


# Constraints



# Note



# Source


