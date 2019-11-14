
# Content

方老师准炸毁学校,学校可以被看做是一个图包含$N$个顶点和$M$条边(顶点从$0$开始标号)，方老师发明了一个方老师炸弹。

这个炸弹可以炸毁某一个节点和与这个节点相连的所有边。但是方老师现在很彷徨，他想使得使用了一个炸弹之后学校炸成更多的联通块。

方老师想知道把学校炸成尽量多块的放置点的前$K$个顶点是哪些，这些点可以被把学校炸成多少个联通块？

# Standard Input

* 多组数据，`EOF`结束。
* 第$1$行：$N$和$M$和$K$
* 第$2$到第$M+1$行：每一行$2$个数$U\_i$和$V\_i$，表示$U\_i$到$V\_i$之间有一条边。

# Standard Output

$K$行，每行$2$个数$Pos\_i$，$C\_i$，用空格隔开，表示在$Pos\_i$点放置炸弹可以把学校炸成$C\_i$块。如果对于不同的点可以把学校炸成相同多块，优先输出编号小的顶点。

每组数据后面输出一个空行

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
<tr><td>8 8 4
0 4
1 2
2 3
2 4
3 5
3 6
3 7
6 7</td><td>2 3
3 3
4 2
0 1</td></tr></table>


# Constraints



# Note

$K \leq N\leq 10000$，$M\leq 100000$

# Source


