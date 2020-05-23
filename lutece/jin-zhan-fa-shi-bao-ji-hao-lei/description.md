
# Content

现在有 $n$ 只怪物排成一排，第 $i$ 只怪物的伤害值为 $a_i$ ，法师可以做两种操作：

1. 施加魔法将一对相邻并且伤害值相同（$a_i = a_{i+1}$）的怪物合并为一只伤害值为 $a_i+1$ 的怪物，不消耗体力值。
2. 使用暴击击杀一只怪物，无论怪物的伤害值为多少，均消耗一点体力值。

为了体验连续暴击的快感，法师决定先合并怪物，再暴击掉剩下的怪物。请你算一算，法师击杀所有怪物最少需要多少点体力值？

# Standard Input

第一行一个整数 $n(1\le n\le 500)$。

接下来一行 $n$ 个整数 $a_1$ 到 $a_n$，整数 $a_i(1\le a_i \le 1000)$，表示第 $i$ 个怪物的伤害值。

# Standard Output

输出一个整数，击杀所有怪物最少消耗的体力值。

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
<tr><td>7
1 1 2 2 2 1 1
</td><td>2
</td></tr></table>


# Constraints



# Note



# Source


