
# Content

~~这是一道实打实的硬核数据结构，就不BB了，看要求，懂题意~~。

给一个长度为$n$的数组$a$和一个长度为$n-1$的数组$b$，你需要完成以下两种操作。

$1.$将$a[i]$增大到$a[i]+x$.如果$a[i+1]<a[i]+b[i]$，那么$a[i+1] = a[i] + b[i]$，然后如果$a[i+2]<a[i+1]+b[i+1]$，那么$a[i+2] = a[i+1] + b[i+1]$。$a[i+3],a[i+4]....a[n]$以此推类。

$2.$询问$a$数组中区间$[l,r]$的区间和。

我们保证一开始$a[i]+b[i] \leq a[i+1]$。

# Standard Input

第一行一个$n$，表示$a$数组的长度。

第二行$n$个数分别为$a1,a2,a3...an$，表示$a$数组的元素大小。

第三行$n-1$个数分别为$b1,b2,b3...$,表示$b$数组的元素大小。

第四行一个$q$，表示操作数量。

接下来$q$行：

$1.$格式为$1$ $p$ $x$表示将$a[i]$增大$x$.

$2.$格式为$2$ $l$ $r$表示询问$a$数组$[l,r]$的区间和。

# Standard Output

对于每个2操作，输出区间和。

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
1 2 3
1 -1
5
2 2 3
1 1 2
2 1 2
1 3 1
2 2 3</td><td>5
7
8
</td></tr></table>


# Constraints

$2 \leq n \leq 1e5$

$-1e9 \leq ai \leq 1e9$

$-1e6 \leq bi \leq 1e6$

$1 \leq q \leq 1e5$

对于第一类操作：$1 \leq p \leq n, 0 \leq x \leq 1e6$

对于第二类操作：$1 \leq l \leq r \leq n$

# Note



# Source


