
# Content

众所周知，柱爷既会炒股，又会抢银行，所以柱爷很有钱。

传说柱爷有$N$份宝藏，但没人知道它们藏在哪里。因为柱爷用特殊的方式把它们藏在了多个地方。

柱爷先把编号为$1..N$的宝藏按顺序排成一排，每份价值为$A_i$。然后把它们合并成许多份，只有相邻的几个宝藏才能合成一份。每份宝藏放在一个地方。

显然，每份宝藏的价值越高，越不安全。柱爷认为，假设某份宝藏由$A_{l..r}$组成，这份宝藏被发现的概率可用下面的公式算出，其中$M$是一个常数。

$$ (\sum_{i=l}^r A_i)^2 + M $$

这个值越大，表示越有可能被发现。所以柱爷希望所有宝藏被发现概率之和最小，请问这个最小值是多少。

# Standard Input

第一行输入两个数$N，M$。

第二行输入$N$个数，表示每个宝藏的价值。

数据保证：

* $1 \leq N \leq 500 000，0 \leq M \leq 1000$

* $0 \leq A_i \leq 1000$

# Standard Output

输出一行，概率之和的最小值

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
<tr><td>5 6
5 9 5 1 2</td><td>164
</td></tr></table>


# Constraints



# Note

样例：

划分为$ 5 | 9 | 5 | 1,2$

$[5^2+6]+[9^2+6]+[5^2+6]+[(1+2)^2+6]=164$

# Source


