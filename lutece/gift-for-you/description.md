
# Content

**Hey guys, we have a gift for you~**

但是这要根据你队伍的比赛排名领奖，`fatdog`参加了 $n$ 场吹气球比赛（与此同时他的队友写了 $n$ 场比赛的代码），每场吹气球比赛有 $m$ 支队伍，礼物的分发由`fatdog`最终的总排名决定，总排名计算方式如下：

设`fatdog`第 $i$ 比赛的排名为 $rk_i$ ，他的总得分就为 $P = \sum{_{i=1}^n}rk_i$ ，则他的排名就为：$rank$ = 队伍总得分**严格小于** $P$ 的队伍数 + 1。

`fatdog`很想知道自己能领到什么样的奖励，但是他是个弱智，他只记得自己每场的排名。

快帮`fatdog`算一下他总排名的期望为多少。

# Standard Input

第一行包含两个整数 $n$ 和 $m$ ($1\leq n\leq 100, ~2\leq m \leq 1000$)。

下一行包含 $n$ 个整数，第 $i$ 个整数 $rk_i$ 代表`fatdog`第 $i$ 场比赛的排名 ($1\leq rk_i \leq m$)。

# Standard Output

输出一个浮点数，表示`fatdog`总排名的期望。

结果四舍五入保留 $6$ 位小数。

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
<tr><td>4 10
2
1
2
1
</td><td>1.000000</td></tr></table>


# Constraints



# Note

`fatdog`总得分为 $2+1+2+1=6$，在他得分的前提下不可能存在另一支队伍的得分小于 $6$，所以他的总排名为 $0+1=1$。

# Source


