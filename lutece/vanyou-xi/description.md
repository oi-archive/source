
# Content

`eom`和`moe`在van取石子游戏。桌面上有n堆石子，每堆石子有$x_i$个，每次轮到一个人的时候他可以取走一堆石子。石堆的选取顺序给定并正好形成一个有向树，即当前选取的石堆必须是上一个人选取的石堆的儿子，第一个选的人只能选位于树根的石堆。`eom`和`moe`的选取策略有所不同，`eom`希望游戏结束时自己石子尽可能多的情况下`moe`手中的石子尽可能少，`moe`则希望`eom`手中的石子尽可能少的前提下自己手中的石子尽可能多。如果两人都按照最优策略取石子，请你计算出游戏结束时两人手中分别有多少石子。

# Standard Input

第一行为一个字符串"eom"或"moe"，表明谁先取。

第二行为一个正整数n(n&le;1e6)表示桌面上有多少堆石子。

第三行为n个正整数，第i个表示第i堆共有$x_i$个石子。

接下来n-1行每行两个整数u和v，表示石堆u被取走之后下一个人可以选取石堆v。

# Standard Output

在一行中输出两个个整数表示游戏结束时而`eom`和`moe`手中分别有多少石子。

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
<tr><td>eom
6
1 3 5 3 4 2
1 2
1 3
3 4
3 5
5 6</td><td>1 3</td></tr></table>


# Constraints

n&le;1e6

$x_i$&le;1e9

# Note



# Source


