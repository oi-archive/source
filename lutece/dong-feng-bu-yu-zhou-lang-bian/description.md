
# Content

“揽二乔于东南兮，乐朝夕之与共”

一首铜雀台赋，将愤怒与恐惧散播在了孙吴大军之中。

对抗曹军，万事俱备，只欠东风。

现在已经找到$n$个风眼，这些风眼的东风有强有弱，诸葛亮说他每次祈风都能够将一段风眼的东风增强，但需人去帮他布阵。同时他需要时刻掌控风眼的状况，以确定下一步的计划，所以还需要知道一段风眼的强度之和。

借东风，此乃逆天之术，施术者会折阳寿不说，布阵者更是会受十倍之伤。

“何人能当此任？”

“在下愿往，大都督。”

“你是？”

“在下一无名小卒，来自跳蚤街。”

# Standard Input

第一行两个整数$n$，$m$，表示有$n$个风眼，诸葛亮一共祈风或询问了$m$次。

第二行$n$个整数，第$i$个数$a_i$表示第$i$个风眼已有东风的强度。

接下来$m$行，每行开始先读入一个整数$s_i$，指明这是一次询问还是一次祈风。

$s_i = 0$，表明这是一次询问，然后读入两个整数$l_i,r_i$，表示询问$[l_i,r_i]$区间中风眼的东风强度之和。

$s_i = 1$，表明这是一次祈风，然后读入三个整数$l_i,r_i, w_i$，表示把$[l_i,r_i]$区间中每个风眼的东风强度提升$w_i$。

$1 \leq n,m \leq 100000,0 \leq a_i \leq 10000,0 \leq w_i \leq 10000, 1 \leq l_i \leq r_i \leq n$

# Standard Output

有多少询问就输出多少行，每行输出一个整数，作为对该询问的回答。

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
<tr><td>5 4
1 2 3 4 5
1 2 3 2
0 3 4
1 4 5 3
0 2 4</td><td>9
16</td></tr></table>


# Constraints



# Note



# Source


