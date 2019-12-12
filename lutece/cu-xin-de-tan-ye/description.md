
# Content

谭爷喜欢把整数分解质因数，如$12=2^2*3$，$1024=2^{10}$，特别地，$1=1$。

有一天谭爷心血来潮，把$1$到$n$所有整数的分解形式写在纸上，然后计算它们的和。

但粗心的谭爷把公式中的幂运算的指数看成了连接在底数后面的数字，如把$2^2*3$看成了$22*3=66$，把$2^{10}$看成了$210=210$，因此结果与真实答案大相径庭。

谭爷没有发现这一点，并愚蠢的继续算下去。

坐在谭爷旁边的你看不下去了，写个程序帮谭爷算出他最终得到的结果。

# Standard Input

输入一个整数$n$，$1\leq n \leq 10^7$

# Standard Output

输出谭爷算出来的结果。

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
<tr><td>12</td><td>188</td></tr></table>


# Constraints



# Note

对于样例

普通人眼中的式子为$1+2+3+2^2+5+2*3+7+2^3+3^2+2*5+11+2^2*3=78$

谭爷眼中的式子为$1+2+3+22+5+2*3+7+23+32+2*5+11+22*3=188$

# Source


