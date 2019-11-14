
# Content

数学考试后大佬们总是喜欢凑在一起对答案，如果不小心听到了大佬们的讨论极有可能受到巨大的心理创伤，从而茶饭不思。。。

蒟蒻$Pxt$在考完试后总会快速地离开教室，以免受到大佬们的波及。但是不堪好奇心的折磨，$Pxt$会向大佬打听一些题目的答案。

为了避免造成巨大的心理创伤，$Pxt$的询问策略如下。

假设存在一个长度为$n$的整数序列，代表该次考试有$n$题，每题的答案为一整数。

每一次询问某个连续子串的和是奇数还是偶数 。

由于询问的方式过于奇怪，大佬给出的回答可能有错。

请找出第一个$i$，使得前$i+1$条询问不可能同时满足。如果都可以满足，输出$ORZQHQH$。

# Standard Input

第一行一个整数$n$，表示数列的长度。

第二行一个整数$m$，表示询问总数。

接下来$m$行，每行形式如下：a b odd/even，表示从第$a$个数到第$b$个数之和为奇（$odd$）或偶（$even$）。

# Standard Output

如果所有询问不能同时满足，且第一个不能满足的信息是第$i+1$条，输出$i$。

如果所有询问能同时满足，输出$ORZQHQH$。

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
5 
1 2 even
3 4 odd 
5 6 even
1 6 even 
7 10 odd</td><td>3</td></tr></table>


# Constraints

$n≤1,000,000$

$m≤20,000$

# Note



# Source


