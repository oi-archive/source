
# Content

谷歌、百度等搜索引擎已经成为了互连网中不可或缺的一部分。在本题中，你的任务也是设计一个搜索论文的搜索引擎，当然，本题的要求比起实际的需求要少了许多。

本题的输入将首先给出一系列的论文，对于每篇论文首先给出标题，然后给出它被引用的次数。然后会有一系列的搜索询问，询问标题中包含特定关键词的论文有哪些。

每一个询问可能包含多个关键词，你需要找出标题包含所有关键词的论文。

`包含`必须是标题中有一个词正好是给定的关键词，不区分大小写。

对每个询问，都按被引用的次数从多到少输出满足条件的论文的标题。如果有被引用的次数相同的论文，则按照论文在输入中的顺序排列，先给出的论文排在前面。

# Standard Input

输入包含多组数据。

每组数据首先有一行包含一个整数$N$($1\leq N\leq 1000)$，表示论文的数目，$N=0$表示输入结束。每组论文的信息第一行是论文的标题，由字母（大小写均可）和空格组成，不超过$10$个词，每个词不超过$20$个字符，标题总共不超过$250$个字符。第二行是一个整数$K$($0\leq K\leq 10^8$)，表示它被引用的次数。

在论文信息结束以后，有一行包含一个整数$M$($1\leq M\leq 100$)，表示询问的数目。

接下来有$M$行，每行是一个询问，由$L$($1\leq L\leq 10$)个空格分开的词构成，每个词不超过$20$个字符。

# Standard Output

对每个询问，按照题目给定的顺序输出满足条件的论文的标题；如果没有满足条件的论文，就不输出。在每组询问的输出之后输出一行`***`，在每组数据的输出之后输出一行`---`。

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
<tr><td>6
Finding the Shortest Path
120
Finding the k Shortest Path
80
Find Augmenting Path in General Graph
80
Matching in Bipartite Graph
200
Finding kth Shortest Path
50
Graph Theory and its Applications
40
6
shortest path
k shortest path
graph
path
find
application
0</td><td>Finding the Shortest Path
Finding the k Shortest Path
Finding kth Shortest Path
***
Finding the k Shortest Path
***
Matching in Bipartite Graph
Find Augmenting Path in General Graph
Graph Theory and its Applications
***
Finding the Shortest Path
Finding the k Shortest Path 
Find Augmenting Path in General Graph
Finding kth Shortest Path
***
Find Augmenting Path in General Graph
***
***
---</td></tr></table>


# Constraints



# Note



# Source


