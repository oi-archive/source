
# Content

Cjj 参加了国际城市设计大赛，也就是 ICPC (International City Project Contest)。比赛规则如下：

城市中有 $n$ 个地区，给出 $m$ 条可供选择的道路，每条道路连接两个不同的城市，并有一定的建造花费。选手需要选择出若干条道路，使得这些道路能让所有地区互相连通，并且总花费尽可能小。

这对 Cjj 来说并不是什么难题。然而，他得知他的好朋友 Macaron_lin 也参加了这次比赛。他知道 Macaron_lin 肯定会选择总花费最少的方案，而他并不想和他的朋友发生竞争。因此，他想选择一种方案，使得在花费多于他朋友的方案的情况下，花费尽可能小。你能告诉他这种方案的花费是多少么？

# Standard Input

第一行两个整数 $n$ 和 $m$ ($2 \le n \le m \le 3\times10^5$)，表示地区个数以及可供选择的道路数。

接下来 $m$ 行，每行 $3$ 个整数 $u,v,w$ ($1 \le u,v \le n, 1 \le w \le 10^9$)，表示一条连接 $u$ 和 $v$ 的道路，花费为 $w$。

输入数据保证有解。

# Standard Output

一行一个整数，表示 Cjj 所选方案的花费。

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
<tr><td>3 3
1 2 3
2 3 3
1 3 2</td><td>6</td></tr></table>


# Constraints



# Note



# Source


