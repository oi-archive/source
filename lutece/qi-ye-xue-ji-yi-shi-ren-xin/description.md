
# Content

Nim游戏是一种传统的游戏，其套路也渐渐被人熟悉，大家都不喜欢这种一眼就看出输赢的游戏，因此有人修改了Nim游戏的规则：

1.这仍然是一个二人游戏，有多堆石子，双方轮流选取一堆从中拿走a个石子。

2.存在一个集合$S$，$a$只能从集合$S$中选取,第i个元素为$s_i$.

众所周知，一局比赛的输赢是不能让人信服的，所以需要多局的较量，所以双方会进行$m$场比赛,每场比赛的初始局势都不同，然而dalao总是能看穿一切，当看到局势的时候就知道了结果。

# Standard Input

第一行是一个数$k$,表示集合$S$的大小.

第二行是k个数表示集合中的元素。

第三行是一个数$m$,表示有$m$局比赛。

接下来是m行，每行第一个数$m_i$表示第i局初始有$m_i$堆石子，之后有$m_i$个数，代表每堆石子有h_i个。

($1 \leq k \leq 100$,$1 \leq s_i \leq 10000$,$1 \leq m_i \leq 100$,$1 \leq h_i \leq 10000$)

# Standard Output

对于每一局，如果先手胜则输出“win！”，后手胜则输出“lose！”，每一局的输出占一行。

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
<tr><td>2 
2 5
3
2 5 12
3 2 4 7
4 2 3 7 12</td><td>lose!
win!
win!</td></tr></table>


# Constraints



# Note

By Qyitong

# Source


