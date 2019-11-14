
# Content

`jjjjddw`是新加入魂天神社的菜鸟雀洁。

某一天的南风局，雀洁`jjjjddw`在东一局就被默听的二阶堂美树飞了出去。`xzlnb`发现`jjjjddw`的防守能力实在太弱，于是`xzlnb`想训练一下`jjjjddw`。`xzlnb`拿出若干堆牌(某一堆牌的数量可能为0)，标号从$1$到$n$，准备和`jjjjddw`玩一个游戏。由`jjjjddw`先手，两人轮流进行操作：选择一堆牌，将正数数量的牌拿走。最后无法操作的人被判为失败。 `xzlnb`稍加思索，觉得这个游戏简直就是铜间难度，于是他让游戏在一颗树上进行，改变了操作规则：除了标号为1的牌堆之外，任何牌堆都有一个父亲，每次选择一堆牌，将正数数量的牌移动至父亲而不是拿走。

`xzlnb`告诉`jjjjddw`：如果给定初始的状态，真正的雀士可以轻易计算出自己是否会放铳并且作出相应对策。现在`jjjjddw`希望你能够帮助他确定，对于给定的初始状态，假定双方采取最优策略DP（打牌），`jjjjddw`是否会DP（点炮）。

# Standard Input

一组数据。

第一行一个整数$n$。

第二行$n - 1$个整数，第$i$个代表第$i + 1$个牌堆的父亲编号$father_i$。

第三行$n$个整数，第$i$个代表第i个牌堆的麻将数量$a_i$

# Standard Output

`YES`or `NO` 表示jjjjddw能否避铳

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
<tr><td>4
1 1 1
3 1 2 3</td><td>NO</td></tr></table>


# Constraints

$1\leq{n}\leq100,000$

$1\leq{a_{i}}\leq1,000,000,000$

# Note



# Source


