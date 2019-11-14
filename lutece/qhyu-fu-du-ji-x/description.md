
# Content

qh今天想杀一批复读机。

qh把最近几天的聊天记录扒了出来，用一种神奇的编码方式将聊天记录转换成了由小写字母组成的字符串。

记代表第$i$段聊天记录的字符串为$S_i$。

对于每条聊天纪录他想知道这条聊天纪录总共被复读了多少次，即这段发言在所有聊天纪录中的出现次数。

检查聊天记录非常耗时，于是qh把这件事丢给了后缀复读机。

后缀复读机有一万个ddl要赶，没时间看聊天记录。

你能帮后缀复读机解决检查聊天记录的问题吗？

# Standard Input

第一行有一个数$N$，代表总共有$N$条聊天纪录。

接下来$N$行，每行有一条由小写字母组成的字符串$S_i$，代表第$i$段聊天纪录。

# Standard Output

共输出$N$行，即每条聊天纪录在所有聊天纪录中的出现次数。

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
<tr><td>10
orzqh
orzqhqh
orzqhqh
orzqhqh
orzqhqhorzqhqhorzqhqh
zhtxdy
txdy
zhtxdyzhtxdyzhtxdy
zhtxdyzhtxdy
dy</td><td>7
6
6
6
1
6
7
1
3
8
</td></tr></table>


# Constraints

$1\leq N \leq 10^6$

记第$i$条发言为$T_i$，则有：

$1 \leq |T_i| \leq 10^6$

$N \leq \sum_{i=1}^{N}{|T_i|} \leq 10^6$

# Note



# Source


