
# Content

经过改造后的绫波，再次玩起[鱼雷游戏](https://acm.uestc.edu.cn/contest/83/problem/H)，这次，她还是面对一面长墙，墙上有 $n$ 个点（编号 $1\sim n$），每个点都带有一个特定的数值（可能为负数）。

这次在每一轮游戏中，綾波需要使用鱼雷把一个区间（$[l,r]$）内的所有点的数值变为 $c$，每个点需要消耗一枚特制鱼雷。

改造后的綾波，雷击能力非常逆天，可以轻松地同时击中任意多个不等距的点，从而不浪费任何鱼雷在那些数值本来就为 $c$ 的点上面。当然，她也不可能因为没有命中而浪费鱼雷。

尽管如此，綾波在获得了墙面上各点初始数值和每轮的目标后，还是希望指挥官能帮她计算她每一轮需要的鱼雷数量，你能帮帮她吗？

# Standard Input

第一行，整数 $n$，表示一开始墙面上的点个数
第二行，$n$ 个整数，依次表示各点的初始数值
第三行，整数 $m$，表示游戏的轮数
后面 $m$ 行，每行四个整数 $l$，$r$，$c$，$d$ 表示目标区间 $[l,r]$ 、目标值 $c$

# Standard Output

$m$ 行，每行一个整数，表示每轮需要消耗的鱼雷数量

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
<tr><td>5
123 2 42 46 -248
3
1 5 2
1 5 5
5 5 4</td><td>4
5
1</td></tr><tr><td></td><td></td></tr></table>


# Constraints

$0<n,m,k\leq 10^5$
$1\leq l\le r \leq n$
其他数均在 $int$ 范围内，即 $-2^{31}\leq others < 2^{31}$

# Note

本题正解不唯一哦

# Source


