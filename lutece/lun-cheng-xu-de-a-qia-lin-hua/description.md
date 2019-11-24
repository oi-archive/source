
# Content

又有讨厌的熊孩子往阿卡林的桌子上乱堆东西了（“什么？那桌子旁边有人？”）。

现在桌子上堆了整整$n$本书呢，反正也没什么事做，我们就接着玩儿吧。

下面我告诉你两种操作：

一种是直接往书堆顶部再放一本书。

另一种是把最顶端的$K$本书整个翻转过来（如果桌子上一共都不够K本书的话，就直接把整个书堆倒过来好了）。

第一种操作写作$ADD(S)$，$S$是放的书的名字。
第二种操作写作$ROTATE$。

在玩儿的过程中，书的总数不会超过$40000$，所有书的名字都由非空的大写字母组成，长度不超过$3$，注意书名可能会有重复。

# Standard Input

输入文件包括多组数据，每组数据的第一行包括三个整数$N,M,K$ ($0 \leq N \leq 40000$; $0 \leq M \leq 100000$; $0 \leq K \leq 40000$). 接下来N行从上往下给出了$N$本书的名字。接下来$M$行，每行给出一种操作。

# Standard Output

所有操作完成后，从上到下依次输出每本书的书名。

相邻两组数据中间请输出一个空行。

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
<tr><td>2 3 2 
A 
B 
ADD(C) 
ROTATE 
ADD(D)</td><td>D 
A 
C 
B</td></tr></table>


# Constraints



# Note



# Source


