
# Content

在干完 $The\,Big\,One$（一票大的）之后，劫犯们得准备逃跑路线了。

城市可以看作 $n$ 个点 $m$ 条边的无向图，节点编号为 $0$ 到 $n-1$，其中有 $k$ 个点为安全屋，劫犯们只要到达其中一个安全屋就能摆脱警察的追捕。

劫犯们从联合储蓄（节点 $0$）出发，希望能在最短的时间内到达安全屋。

但是警察对劫犯紧追不舍，每当劫犯到达一个节点，警察就立刻封锁与该点相连的边。

由于警力有限，对于当前点警察最多能够封锁与其相连的 $d$ 条边。

现在劫犯想知道，在最坏情况下，他们能到达安全屋的最短时间。

# Standard Input

第一行四个整数 $n$ 、$m$ 、$k$ 和 $d$，含义如上文所描述。

接下来 $m$ 行每行三个整数 $u$ 、$v$ 和 $w$，表示节点 $u$ 和 $v$ 之间有一条边，且通过该条边要花费 $w$ 的时间。

接下来一行有 $k$ 个整数，表示安全屋所在节点编号。

$1 \leq n \leq 100000$，$1 \leq m \leq 1000000$，$0 \leq k \leq n$，$0 \leq d \leq m$，$0 \leq u$ 、$v < n$，$0 \leq w \leq 10000$ 。

# Standard Output

若劫犯们不能到达安全屋，则输出 $-1$ 。

否则输出最坏情况下劫犯们到达安全屋的最短时间。

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
<tr><td>3 3 1 0
0 1 1
1 2 1
0 2 3
2</td><td>2</td></tr><tr><td>3 3 1 1
0 1 1
1 2 1
0 2 3
2</td><td>-1</td></tr></table>


# Constraints



# Note



# Source


