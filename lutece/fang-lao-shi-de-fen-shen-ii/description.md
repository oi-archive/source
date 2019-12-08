
# Content

方老师计算出了走路时间最长的那个分身所用的时间。于是有个特殊的分身（据说是方老师真身！）就不想如此古板的走最短路了！由于这个分身的特殊性，这个分身对于单向边可以当双向边走。但是这个特殊的分身想走最短路的同时，要求至少经过$k$条边。

# Standard Input

有多组数据

第一行两个整数$n$，$m$（$1\leq n\leq 5000$，$1\leq m\leq 100000$）表示有$n$个教室，$m$条边。

接下来$m$行，每行$3$个数，$u$，$v$，$t$。表示$u$，$v$间有一条长度为$t$的边。

最后一行三个整数$s$，$t$，$k$，表示起点、终点、至少经过$k$（$k\leq 50$）条边。

# Standard Output

一个整数，表示最短路径长度。如果无解输出$-1$。

每组数据占一行。

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
<tr><td>4 4
1 2 1
2 3 2
1 3 100
3 4 1
1 3 5</td><td>7</td></tr></table>


# Constraints



# Note



# Source


