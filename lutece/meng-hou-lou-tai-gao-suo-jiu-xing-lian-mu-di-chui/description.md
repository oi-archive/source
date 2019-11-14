
# Content

给你一个有$n$个点和$m$条边的无向连通图,每条边都有一个权值$w$.    
我们定义，对于一条路径，它的**Charm value**为该路径上所有边的权值的最大值与最小值的差.   
询问从$1$到$n$的所有路径的**Charm value**的最小值.

# Standard Input

第一行有两个整数$n,m\left ( 1\leq n\leq 200,n - 1\leq m\leq 1000 \right )$，表示该图有$n$个点和$m$条边.   
接下来$m$行，每行三个整数$u,v,w\left ( 1\leq u,v\leq n,1\leq w\leq 1000000 \right )$，表示点$u$和点$v$之间有一条权值为$w$的边.

# Standard Output

输出一个数，即从$1$到$n$的所有路径的**Charm value**的最小值.

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
3 4 1
2 3 2
1 2 4
2 4 3</td><td>1</td></tr></table>


# Constraints



# Note



# Source


