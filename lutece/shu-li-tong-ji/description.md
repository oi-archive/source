
# Content

被概率论整的死去活来的`forgottencsc`总算开始学数理统计了。他不想做作业，所以把作业丢给了你。

你需要对一个长度为$N$的数列做以下三种操作。

1. 将下标在区间$[L,R]$内的数全部加上一个定值$k$。

2. 将下标在区间$[L,R]$内的数加起来并输出。

3. 统计下标在区间$[L,R]$内的数的极差（最大值与最小值的差）。

数列中的数在开始时全为0。

# Standard Input

第一行有两个数$N,Q$，代表数列长度和操作次数

接下来的$Q$行，每行最开始有一个数$o$。

若$o=1$，则接下来有三个数$L,R,k$，代表一次操作1。

若$o=2$，则接下来有两个数$L,R$，代表一次操作2。

若$o=3$，则接下来有两个数$L,R$，代表一次操作3。

# Standard Output

对于每一个操作2或3，你需要输出相应的结果。

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
<tr><td>3 4
1 1 1 10
1 3 3 -10
2 1 3
3 1 3</td><td>0
20</td></tr></table>


# Constraints

$1 \leq N,Q \leq 10^6$

$1 \leq L \leq R \leq N$

$0\leq |k| \leq 10^6$

# Note

时限有点紧，请注意常数优化。（仍然是标程的两倍以上，而且标程用的是cin/cout）

读入数据量巨大，请使用scanf/printf。

仍想使用cin/cout的选手请在程序开头加上ios::sync_with_stdio(false); cin.tie(0);

有同学反映用%I64d输出long long会导致WA，请考虑使用%lld。

# Source


