
# Content

qh今天想杀很多批复读机。

qh把最近几天的聊天记录扒了出来，用一种神奇的编码方式将聊天记录转换成了由小写字母组成的字符串。

qh每次检查两段聊天记录，如果第一段在第二段中出现了很多次，他就会杀一批复读机。

检查聊天记录非常耗时，于是qh把这件事丢给了后缀复读机。

后缀复读机有一万个ddl要赶，没时间看聊天记录。

你能帮后缀复读机解决检查聊天记录的问题吗？

# Standard Input

第一行有两个数$N,Q$，代表聊天记录长度为$N$,且总共有$Q$次询问。

接下来一行是一个长为$N$，由小写字母组成的字符串。

接下来$Q$行，每行有四个数$L1,R1,L2,R2$，分别代表qh选择的两段聊天记录是$S$的哪两个子串。

# Standard Output

对于每次询问，你需要输出$S_{L1...R1}$在$S_{L2...R2}$中出现了多少次（允许重叠）。

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
<tr><td>6 4
aababb
4 4 1 6
2 3 1 5
6 6 1 4
1 2 2 3</td><td>3
2
1
0
</td></tr></table>


# Constraints

$1\leq N,Q\leq 5\times 10^5$

$1 \leq L1 \leq R1 \leq N$

$1 \leq L2 \leq R2 \leq N$

# Note

$S_{L...R}$是由$S$中第$L$个字符到第$R$个字符组成的子串。

# Source


