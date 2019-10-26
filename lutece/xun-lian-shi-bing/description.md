
# Content

elfness正在玩一个游戏，在这个游戏里，他掌管着一个王国。

这是一个回合制的游戏，初始的时候elfness没有任何钱，每一回合开始他会获得$a$的金钱，当elfness的金钱大于等于$b$时，elfness会花钱去训练士兵，直到他的钱小于$b$，每训练一个士兵需要花$b$的钱。训练完士兵后进入下一回合。elfness想知道他在整个游戏过程中他钱最多的时刻他有多少钱。

# Standard Input

输入的第一行是一个整数$T$($T\leq 10000$), 表示有$T$组测试数据。

对于每组测试数据，有一行，包含两个整数$A$和$B$($1\leq A,B\leq 10^9$)。
​​

# Standard Output

对于每组测试数据，输出一个整数，表示elfness在钱最多的时刻有多少钱。

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
2 3
7 11</td><td>4
17</td></tr></table>


# Constraints



# Note

对于第一组样例，elfness拥有的金钱数将如下变化：$0\rightarrow 2\rightarrow 4\rightarrow 1\rightarrow 3\rightarrow 0\rightarrow \cdots$所以他最多时有$4$的金钱。

输入量很大，请用`scanf`代替`cin`进行输入。

# Source


