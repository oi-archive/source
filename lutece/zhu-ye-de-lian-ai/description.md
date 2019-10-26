
# Content

她手里有刚刚收到从远方的括号序列__(仅包含__`( ) [ ]`__的序列)__,然而序列已经是一团乱麻,不堪入目,柱爷看到她坐在位子掩面哭泣,便上前安慰一番,她向柱爷提出自己的"无理"申请.

她"蛮横"地要求柱爷计算出:删去这个括号序列的一个子集__(不可以把整个括号序列都删去,那可是她的心爱之物;可以不完全删;子集可能是不连续的;子集可能为∅)__,使得这个括号序列合法的方案数.

这个方案数可能很大,所以她只要求柱爷计算出这个方案数%1000000007就好了(她心疼柱爷,不想让柱爷打高精度).

你能帮柱爷解决这个恋爱中的小小问题吗？

# Standard Input

第一行一个整数$N$，表示括号序列的长度

接下来一行包含一个长度为$N$的括号序列字符串

数据保证:

*  $1\leq N \leq300$

# Standard Output

一个正整数,表示柱爷要回答她的数.

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
()[]</td><td>3</td></tr><tr><td>3
())</td><td>2</td></tr></table>


# Constraints



# Note

合法的括号序列定义如下:

* 如果S是合法序列,那(S)和[S]也是合法序列;
* 如果A和B都是合法序列,那么AB也是合法序列.
* 例如,下面的字符串都是合法序列:
* (), [], (()), ([]), ()[], ()[()]

# Source


