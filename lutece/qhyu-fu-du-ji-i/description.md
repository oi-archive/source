
# Content

qh今天想杀一批复读机。

qh把最近几天的聊天记录扒了出来，用一种神奇的编码方式将聊天记录转换成了由小写字母组成的字符串。

qh将聊天记录分割成了数段，记第$i$段为$S_i$。

对于每一段$S_i$，qh想知道这一段是`前面`几段聊天记录的前缀与几段聊天记录的后缀。

检查聊天记录非常耗时，于是qh把这件事丢给了后缀复读机。

后缀复读机有一万个ddl要赶，没时间看聊天记录。

你能帮后缀复读机解决检查聊天记录的问题吗？

# Standard Input

第一行一个$N$，代表总共有$N$段聊天记录。

接下来$N$行，每行有一个字符串$S_i$。

# Standard Output

对于每段聊天记录$S_i$，输出这段聊天记录为$S_1,S_2,...,S_{i-1}$中几段的前缀/后缀。

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
abcba
ab
ba
a
b
</td><td>0 0
1 0
0 1
2 2
1 1
</td></tr><tr><td>4
aaaa
aaa
aa
a</td><td>0 0
1 1
2 2
3 3
</td></tr><tr><td>3
a
aa
a</td><td>0 0
0 0
2 2</td></tr></table>


# Constraints

$1 \leq N \leq 10^6$

$1 \leq \sum_{i=1}^{n}{S_i} \leq 10^6$

# Note

对于两个长度分别为$n$和$m$的字符串$S,T$，记$S_i$为$S$中第$i$个字符，那么：

$S$是$T$的前缀当且仅当$S_1=T_1,S_2=T_2,...,S_n=T_n$

$S$是$T$的后缀当且仅当$S_1=T_{m-n+1},S_2=T_{m-n+2},...,S_{n-1}=T_{m-n+(n-1)},S_n=T_m$

# Source


