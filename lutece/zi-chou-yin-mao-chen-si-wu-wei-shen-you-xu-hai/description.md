
# Content

一个有$N$个点的无向连通图，有$M$条无向边，每条边有边权$C$，请你删除$M-N+1$条边，使剩下的$N-1$条边形成一棵树，求这$M-N+1$条边的最小边权和。

# Standard Input

第一行两个整数$N,M$,分别表示点和边的个数。

接下来$M$行，每行三个整数$u,v,c$,表示一条由$u$连向$v$的无向边，边权为$c$.

输入保证没有重边和自环。

$(1<=N<=100000,N-1<=M<=min(100000 , \frac{n(n-1)}{2}),1<=u,v<=N,1<=c<=10000)$

# Standard Output

求删除的$M-N+1$条边的最小边权和。

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
3 4 3
4 1 4</td><td>1</td></tr></table>


# Constraints



# Note



# Source


