
# Content

众所周知，卿学姐十分擅长数据结构。

一天卿学姐开始研究起二维偏序的问题，卿学姐三下五除二就写了个树状数组解决了。

于是卿学姐开始做三维的问题，搞了个树套树也是过了。

欲求不满的卿学姐直接开始搞五维的偏序，仔细思索之后，卿学姐研究出一种用分块加bitset的做法。

峰回路转，沈宝宝问感觉自己要上天的卿学姐16维偏序怎么做，卿学姐现在还在研究六维偏序，不得不将这个问题交给你。

为了简单起见，现在有$n$个$m$维01向量，定义向量$u$大于等于向量$v$，当且仅当向量$u$中的每个分量都大于等于$v$中对应位置的分量，即：

$$u\_i\ge v\_i,1\le i \le m$$

现在问这个向量序列中有多少个子序列是单调不减的子序列。

由于答案可能很大，所以输出结果取模1e9+7

# Standard Input

第一行两个整数$n,m$，分别表示向量的个数和向量的维度。

接下来$n$行$m$列，第$i$行为一个$01$的字符串，长度是$m$，表示第$i$个向量

$1\le n \le 200000,1\le d \le 16$

# Standard Output

输出一个整数，表示单调不减子序列的个数

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
<tr><td>3 2
00
00
11</td><td>7</td></tr><tr><td>4 3
110
100
011
101</td><td>5</td></tr></table>


# Constraints



# Note

对于第二个样例来说，如果子序列最后的长度是1，我们总共能构造4个，如果最后的长度是2，我们能构造一个{100,101}。

# Source


