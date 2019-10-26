
# Content

有$N$个节点，标号从$1$到$N$，这$N$个节点一开始相互不连通。第$i$个节点的初始权值为$a\_i$，接下来有如下一些操作：
* `U x y`: 加一条边，连接第$x$个节点和第$y$个节点
* `A1 x v`: 将第$x$个节点的权值增加$v$
* `A2 x v`: 将第$x$个节点所在的连通块的所有节点的权值都增加$v$
* `A3 v`: 将所有节点的权值都增加$v$
* `F1 x`: 输出第$x$个节点当前的权值
* `F2 x`: 输出第$x$个节点所在的连通块中，权值最大的节点的权值
* `F3`: 输出所有节点中，权值最大的节点的权值

# Standard Input

输入的第一行是一个整数$N$，代表节点个数($N\leq 300000$，$Q\leq 300000$)。

接下来一行输入$N$个整数，$a\_1, a\_2,\cdots , a\_N$($-1000\leq a\_1, a\_2,\cdots , a\_N\leq 1000$)，代表$N$个节点的初始权值。

再下一行输入一个整数$Q$，代表接下来的操作数。

最后输入$Q$行，每行的格式如题目描述所示,其中$-1000\leq v\leq 1000$。

# Standard Output

对于操作`F1`, `F2`, `F3`，输出对应的结果，每个结果占一行。

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
<tr><td>3
0 0 0
8
A1 3 -20
A1 2 20
U 1 3
A2 1 10
F1 3
F2 3
A3 -10
F3</td><td>-10
10
10</td></tr></table>


# Constraints



# Note



# Source


