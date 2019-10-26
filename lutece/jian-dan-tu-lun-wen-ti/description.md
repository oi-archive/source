
# Content

给出一个无向图，该图由$n$个点和$m$条边组成，每个点和每条边都有一个权值.  
对于该图的任意一个子图，我们定义$A$是该子图的点权和，$B$是该子图的边权和，$C=\frac{A}{B}$是该子图的$power$值,如果$B=0$，则$C=0$。现在，你需要找出该图中具有最大$power$值的**连通**的[导出子图](https://en.wikipedia.org/wiki/Induced_subgraph).  
其中，图$G$的导出子图$ {G}'$满足$:$  
$ {G}'$的点集是$G$的点集的子集.  
对于$G$中的任意一条边，如果该边的两个端点都属于$ {G}'$，那么该边一定属于$ {G}'$.

# Standard Input

第一行输入两个整数$n,m\left (1\leq n\leq 500,0\leq m\leq \frac{n*\left ( n-1 \right )}{2}  \right )$,分别表示图的点数和边数.  
第二行$n$个整数，第$i$个数表示标号为$i$的点的权值.  
接下来$m$行，每行三个整数$u,v,w\left ( 1\leq u,v\leq n,u\neq v,1\leq w\leq 10^{6} \right )$，表示标号为$u$的点和标号为$v$的点之间有一条权值为$w$的边，保证没有重边和自环.

# Standard Output

输出具有最大$power$值的连通的导出子图的$power$值，保留两位小数

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
<tr><td>3 3
3 2 1
1 2 5
1 3 4
2 3 4</td><td>1.00</td></tr></table>


# Constraints



# Note



# Source


