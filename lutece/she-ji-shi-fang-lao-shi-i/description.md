
# Content

上次由于方老师对维克兹的改动非常令玩家很满意。于是最近，拳头公司又给了方老师新的任务：调整打野英雄(依靠击杀野怪来升级赚钱的英雄)效率问题。`LOL`发展到现在，适合打野的英雄很多。方老师决定通过一个测试来确定每个英雄是否要做较大调整。

首先，将野怪分为三类：初级野怪(三狼，四鬼)，中级野怪(红蓝`buff`)，高级野怪(小龙、大龙)。方老师的具体测试方式为：调整每类野怪的血量，但保证三类怪物的血量总和不变，从而计算每个英雄打野效率看是否在所有英雄中的排名有所变化。为了简化问题，此处将打野效率直接等同于打野时间即杀死所有野怪所需的时间(保证野怪不会还击)。例如对于一个英雄，他对于三类怪物每秒造成的伤害分别为$U,V,W$，三类怪物的血量分别$A,B,C$，那么他的打野效率$W= \frac{A}{U}+\frac{B}{V}+\frac{C}{W}$。现在通过上述修改，对于每一个英雄，如果能使得他的打野效率高于其他所有英雄，那么就认为该英雄通过测试；否则认为其未通过测试。由于时间紧迫，希望你能帮他快速解决这个问题。

# Standard Input

输入的第一行包含一个正整数$n(1 \leq n \leq 100)$,表示打野英雄总数。接下来的$n$行，每行包含三个正整数$u\_i,v\_i,w\_i(1 \leq  u\_i,v\_i,w\_i \leq 10000)$分别表示英雄每秒对三类野怪分别造成的伤害值。

# Standard Output

输出有$n$行，其中对于第$i$行，如果第i个打野英雄通过测试，那么输出`Yes`，否则输出`No`。

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
10 2 6
10 7 3
6 2 6
8 4 6
1 8 7</td><td>Yes
Yes
No
Yes
Yes</td></tr></table>


# Constraints



# Note



# Source


