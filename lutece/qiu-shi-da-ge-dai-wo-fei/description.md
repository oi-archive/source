
# Content

![Qiushidage Bring Me Fly](/source/lutece/qiu-shi-da-ge-dai-wo-fei/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE0Ny8yMDE1MDUyMzAwMDQzNTA0MDUuanBn.jpg)

然而题目和题面并没有什么关系。

给出$n$个点，$m$条带权无向边，问你从$1$号点到$n$号点的最短路中有多少种走法？

# Standard Input

第一行两个数$n$,$m$分别表示点的个数和边的个数。
（$2\leq n\leq 2000$，$1\leq m\leq2000$）

接下来$m$行，每行3个数$u$,$v$,$w$表示$u$号点到$v$号点有一条距离为$w$的边。（$1\leq u,v\leq n$，$0\leq w\leq 100000$）

数据保证$1$号点能够到达$n$号点，点和边都可以被走多次。

# Standard Output

如果有无穷种走法，输出`-1`。否则输出走法的方案数`mod 1000000009`。

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
1 3 1
2 4 1
3 4 1</td><td>2</td></tr><tr><td>4 4
1 2 1
1 3 1
2 4 1
3 4 0</td><td>-1</td></tr></table>


# Constraints



# Note



# Source


