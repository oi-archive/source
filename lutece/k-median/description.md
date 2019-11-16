
# Content

给出一个$n$个点的树，点上有权，顶点从$1$到$n$编号。其中$1$号节点为根节点，$i$号节点的父亲为$ \lfloor i/2 \rfloor $号节点。


对于树上的一个联通点集的点权组成的集合$A$,定义$k$中位数为：将其中的元素从小到大排序后得到$A_1$ ,$A_2$.....$A_m$

则这个集合的$k$中位数为$A_{\lfloor (m-k+1)/2 \rfloor}$.

现在问题来了,对于${0,1,2......n-1}$中的每个$k$,从这棵树上选取联通块所能获得的最大$k$中位数是多少呢?

# Standard Input

第一行输入一个个整数$n (1\leq n\leq 200000)$ ,分别表示树的点数.  
第二行$n$个整数，第$i$个数表示标号为$i$的点的权值.保证点权是$1$到$n$的一个排列.

# Standard Output

共一行,$n$个整数,依次表示最大的$0$中位数,$1$中位数......$n-1$中位数.

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
1 2 3 4 5</td><td>5 2 2 1 1</td></tr></table>


# Constraints



# Note



# Source


