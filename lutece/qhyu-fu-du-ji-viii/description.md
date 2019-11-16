
# Content

今天qh去打邀请赛啦！复读机们准备乘qh不在疯狂复读！

复读机们准备了一些语录，他们准备在有限的时间内复读尽可能多的语录！

每条语录都有一个愉悦值，这条语录在聊天记录中每出现一次，复读机们就会获得对应的愉悦值!

他们知道qh回来之后会按照复读次数把他们关起来，但仍然准备在有限的时间内通过复读尽可能多的语录来获得愉悦值！

作为资历最老的复读机，你已经有了一个计划。。。。

# Standard Input

第一行有一个数$N$，代表语录数量。

接下来$N$行，每行开头有一个字符串$S_i$，代表一条语录。接下来有一个数$w_i$，代表复读这条语录给复读机们带来的愉悦值。

最后一行又一个数$L$，代表qh将在复读机们复读出长度为$L$的聊天记录后开始杀人。

# Standard Output

输出一个数，代表能够获得的最大愉悦值。

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
aba 5
a 2
ba 3
ab 4
aa 3
5</td><td>30
</td></tr></table>


# Constraints

$1 \le \sum_{i=1}^{n}{|S_i|} \le 500$

$1 \le w_i \le 500$

$1 \le L \le 2000$

# Note

保证所有$S_i$互不相同

# Source


