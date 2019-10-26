
# Content

有$N$个方老师和$N$个缘分，方老师的编号从$1$到$N$,缘分的编号也是从$1$到$N$。

现在每一个方老师都找到了他的缘分(当然一个缘分只能被一个方老师找到)。

现在给出每一个方老师希望找到的缘分的编号(比如$1$号方老师想要$2$号和$3$号缘分)。

求：对于编号为$i$的方老师，当其他的方老师都找到了属于自己的缘分的时候，第$i$个方老师可以找到的缘分编号有哪些？

# Standard Input

* 多组数据，`EOF`结束。
* 第$1$行：$N$
* 第$2$到第$N+1$行：第$i$行第一个数是$k\_i$，$k\_i$是第$i$个方老师希望找到的缘分的个数，接下来$k\_i$个数表示这些缘分。
* 第$N+2$行：$N$个数，表示每个方老师目前寻找到的缘分编号，从$1$到$N$。

# Standard Output

输出共$N$行，
第$i$行行第一个数为$s\_i$，表示第$i$个方老师能够找到的缘分，接下来$s\_i$个数表示这些缘分的编号，从小到大排列。

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
<tr><td>4
2 1 2
2 1 2
2 2 3
2 3 4
1 2 3 4</td><td>2 1 2
2 1 2
1 3
1 4</td></tr></table>


# Constraints



# Note

$N\leq 2000$，所有$k\_i$的和$\leq 200000$

# Source


