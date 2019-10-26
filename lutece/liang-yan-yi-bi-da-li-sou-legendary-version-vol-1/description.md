
# Content

给一个无向图$G$，有$N$个点，$M$条边

现给出起点$S$和终点$T$，问是否存在一条从起点到终点的合法路径.

一条合法路径必须满足下列条件:

* 所经过的边不能重复
* 路径长度必须为$L$

![title](/source/lutece/liang-yan-yi-bi-da-li-sou-legendary-version-vol-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTcxMC8yMDE3MDYwODE0MzY0NTIzNDMwLmdpZg==.gif)

# Standard Input

输入第一行有三个数$N$，$M$，$L$.

接下来$M$行，每行两个整数$u,v$，表示$u$和$v$之间有一条无向边连接

接下来一行两个整数$S,T$，表示起点和终点

数据保证：

* $1 \leq N \leq 500$
* $1 \leq M \leq 505$
* $0 \leq L \leq 10$
* $1 \leq S,T,u,v \leq N$

# Standard Output

输出一行表示答案，如果存在则输出$YES$，否则输出$NO$

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
<tr><td>11 10 10
1 2
2 3
3 4
4 5
5 6
6 7
7 8
8 9
9 10
10 11
1 11</td><td>YES</td></tr><tr><td>6 5 4
1 2
2 3
3 4
4 5
5 6
1 6</td><td>NO</td></tr></table>


# Constraints



# Note

![title](/source/lutece/liang-yan-yi-bi-da-li-sou-legendary-version-vol-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTcxMC8yMDE3MDYwODE0MzUzNDI5MjI5LmdpZg==.gif)大力搜索一发吗少年

![title](/source/lutece/liang-yan-yi-bi-da-li-sou-legendary-version-vol-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTcxMS8yMDE3MDYwOTIxMjUzMDI0NzIuanBn.jpg)

第4组Case为特殊构造，如若TLE，请优化你的玄学算法

# Source


