
# Content

方老师没钱买拖鞋了所以决定去抢银行，城市可以看做$N$个路口和$M$个道路，城市从$1$开始编号。每个路口上有一个`ATM`机器里面有钱。

$M$条单向道路连接城市，方老师从他的据点$P$出发,开始一路抢最后在一个网吧结束自己的旅程。城市里一共有$K$个网吧（网吧都在路口上）。

# Standard Input

* 多组数据，`EOF`结束。
* 第$1$行：$N$和$M$
* 第$2$到第$M+1$行：每一行$2$个数$U_i$和$V_i$，表示$U_i$到$V_i$之间有一条有向边。
* 第$M+2$到第$M+N+1$行：每一行一个数$V$，表示每一个路口的钱数。
* 接下来一个数$P$，表示方老师一开始的据点编号。
* 接下来一个数$K$，表示城市的网吧数目，接下来的一行中有$K$个整数表示网吧所在的路口的编号。

# Standard Output

一个数，表示方老师抢到的最多的钱。当然一个银行只能抢一次。

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
<tr><td>6 7 
1 2 
2 3 
3 5 
2 4 
4 1 
2 6 
6 5 
10 
12 
8 
16 
1 
5 
1 
4 
4 3 5 6</td><td>47</td></tr></table>


# Constraints



# Note

$K \leq N\leq 100000$，$M\leq 300000$

# Source


