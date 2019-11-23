
# Content

qh累了，qh不想亲自动手禁言群友了，于是qh发明了禁言自动机。

qh设置了$N$条经常被复读的语录，如果有复读机复读了这些语录，那么禁言自动机就会自动把说出语录的复读机杀掉。

现在复读机们想知道在有限的长度内有多少种不同的发言会被禁言。

你知道如果你解决不了这个问题，你会被复读机们吊起来%好几天。所以请回答复读机们提出的这个问题。

# Standard Input

第一行一个数$N$，表示qh总共选取了$N$条语录。若发言中包含任意一条或更多条，则发言者会被禁言。

接下来$N$行，每行有一个仅由小写字母组成的字符串$S_i$，代表一条语录。

最后一行有一个数$L$，代表复读机们想知道在所有长度不超过$L$的发言中有多少种会被禁言。

# Standard Output

输出一个数，代表复读机们想要的答案。因为这个数可能很大，所以你需要输出这个数除$10^9+7$的余数。

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
c
bb
2
</td><td>53
</td></tr><tr><td>2
aaa
baa
6
</td><td>140606
</td></tr></table>


# Constraints

$1\leq N \leq 200$

$1 \leq |S_i|  \leq 200$

$N \leq \sum_{i=1}^{N}{|S_i|} \leq 200$

$1 \leq L \leq 10^{18}$

# Note

样例解释：

在第一个样例中，长度为1的发言c与长度为2的发言ac,bc,cc...yc,zc,ca,cb,cd,...,cy,cz与bb都会引发禁言

# Source


