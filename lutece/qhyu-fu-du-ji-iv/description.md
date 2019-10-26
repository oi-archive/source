
# Content

qh今天想杀一批复读机。

qh把最近几天的聊天记录扒了出来，用一种神奇的编码方式将聊天记录转换成了由小写字母组成的字符串。

记代表聊天记录的字符串为$S$。

qh从记忆中挑选了数条经常被复读的语录，如orzqhqh，对于每条语录他想知道这条语录被复读了多少次。

qh不想知道精确的复读次数，所以你只需要输出每条语录在聊天记录中的出现次数，而不用担心不同的出现位置相互重叠。如orzqhqhqh中出现了两次qhqh。

检查聊天记录非常耗时，于是qh把这件事丢给了后缀复读机。

后缀复读机有一万个ddl要赶，没时间看聊天记录。

你能帮后缀复读机解决检查聊天记录的问题吗？

# Standard Input

第一行有一个仅由小写字母组成的字符串$S$，代表聊天记录。

第二行有一个数$N$。

接下来$N$行，每一行有一条仅由小写字母组成的语录$T_i$。

# Standard Output

输出$N$行，即对于每条语录$T_i$，输出这条语录在聊天记录中出现了多少次。

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
<tr><td>orzqhorzzhorzqhqhorzzhzhorzqhqhqh
4
orz
qh
qhqh
zh</td><td>5
6
3
3
</td></tr></table>


# Constraints

$1 \leq |S| \leq 10^6$

$1\leq N \leq 10^5$

记第$i$条语录为$T_i$，则有：

$1 \leq |T_i| \leq 10^5$

$N \leq \sum_{i=1}^{N}{|T_i|} \leq 10^5$

# Note

复读机最近并不是很猖狂，但这并不意味着朴素的算法能够在时间限制内完成检查任务。

# Source


