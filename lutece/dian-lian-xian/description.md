
# Content

图论常用点表示实体，实体间的联系用连线表示。今有$n$个实体排成一圈，编号按顺时针分别为$1$、$2$、$3$、$\cdots$、$n$。给出数$m$，表示下数到第$m$个实体与之连线。下面是$n=5$，$m＝2$时对应的图。

![title](/source/lutece/dian-lian-xian/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTYxLzIwMTQwOTE5MTczMzI3MzA0NS5naWY=.gif)

# Standard Input

输入有一行，有两个用空格隔开的整数$n$和$m$，其中$n$表示实体数，$m$表示按顺时针下数到第$m$个实体与之连线。$2<n<100$，$0\le m\le 200$。

# Standard Output

输出有一行，每一条连线用点对$(u,v)$的形式输出，每个点对后应有一个空格。点对的输出应有序（从第$1$点开始，循环连线的顺序），并且连线不能重复，$(2,4)$和$(4,2)$算作相同的连线。

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
<tr><td>5 2</td><td>(1,3) (2,4) (3,5) (4,1) (5,2)</td></tr></table>


# Constraints



# Note



# Source


