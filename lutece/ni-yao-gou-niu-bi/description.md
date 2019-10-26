
# Content

自从学了线段树以后，beap就以为自己牛逼了，对区间统计问题更是自信满满，号称自己有一把解决区间统计问题的利刃。这时候，CH看不过去了，将自己最近研究的问题“请教”了beap。

一个大小为$N$的数组,有如下的性质:

$a\_0=seed$，$a\_i=(a\_{i-1}\times mul+add)\ mod\ 65536$, ($1 \leq i < N$)。

假设我们要取大小为$K$的连续的一段，那么很显然，共有$N-K+1$段长度为K的子序列。CH想知道这$N-K+1$段子序列里，所有子序列的中位数之和是多少。也就是说，每段里面大小排在第$\frac{K+1}{2}$的数之和是多少。

beap信心满满的想了一个下午以后，发现这个问题不可搞，但是又不想被CH笑话，他只能向你求助了。

# Standard Input

单组测试数据

第一行包含$5$个整数，分别为$seed$，$mul$，$add$，$N$, $K$。

其中$seed,mul,add$的大小都在$0$到$65535$之间（包括$0$和$65535$）

($0 < N \leq 250000$, $0< K \leq 5000$, $K \leq N$)

# Standard Output

对于每组测试数据，输出相应的答案。

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
<tr><td>3 1 1 10 3</td><td>60</td></tr></table>


# Constraints



# Note



# Source


