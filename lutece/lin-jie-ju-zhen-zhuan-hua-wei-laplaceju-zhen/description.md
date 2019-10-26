
# Content

图是研究对象关系(本题考虑的关系是对称的关系)的一个强有力工具。在研究中，一般用结点表示对象，若两对象间有联系，则在两结点间连一条线。利用这种方法，可以把众多问题抽象成图模型，从而利用图论的方法进行解决。

在计算机中存储图，常用的一种方式是邻接矩阵，方法是先对图中所有结点编号：$1,2,3,\cdots ,n$(假设有$n$个结点)，对于矩阵第$i$行第$j$列元素，如果结点$i$与结点$j$有连线，则置该元素为$1$，否则置为$0$。显然，邻接矩阵是$n\times n$的，且该矩阵是对称矩阵。下面是图论中著名的Peterson图及其对应的邻接矩阵。

![title](/source/lutece/lin-jie-ju-zhen-zhuan-hua-wei-laplaceju-zhen/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTI5LzIwMTQwODI1MTgxNTI0NzE3NS5qcGc=.jpg)

对于图中的结点，与之相连的边数，称为该结点的度。在图论研究中，Laplace矩阵也是图的一种常用表示，该矩阵可以由图的邻接矩阵得到，方法是先求出图中各结点的度，再按照结点编号顺序得到一个度对角矩阵，利用度对角矩阵减去邻接矩阵，就得到图的Laplace矩阵。下面是Peterson图的Laplace矩阵。

![title](/source/lutece/lin-jie-ju-zhen-zhuan-hua-wei-laplaceju-zhen/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTI5LzIwMTQwODI1MTgxNTI4NzE3Ni5qcGc=.jpg)

从上面矩阵可以观察出，邻接矩阵为$1$的元素在Laplace矩阵中变为$-1$，对角元素是邻接矩阵对应行的行和。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\leq 200$），表示测试数据的组数。每组测试数据的第一行，是一个整数$R$，表示本组测试数据中邻接矩阵是$R\times R$的，随后是一个$R\times R$的邻接矩阵，每个矩阵元素后有一个空格。其中，$2\leq R\leq 20$。

# Standard Output

对应每组测试数据，输出一个对应的Laplace矩阵，每个矩阵元素后应有一个空格。相邻两个矩阵输出用一个空行隔开。

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
<tr><td>2
5
0 1 0 1 1 
1 0 0 1 0 
0 0 0 1 1 
1 1 1 1 1 
1 0 1 1 1 
6
0 1 0 1 1 0 
1 1 0 1 1 0 
0 0 1 1 0 1 
1 1 1 1 1 1 
1 1 0 1 0 0 
0 0 1 1 0 1</td><td>3 -1 0 -1 -1 
-1 2 0 -1 0 
0 0 2 -1 -1 
-1 -1 -1 5 -1 
-1 0 -1 -1 4 

3 -1 0 -1 -1 0 
-1 4 0 -1 -1 0 
0 0 3 -1 0 -1 
-1 -1 -1 6 -1 -1 
-1 -1 0 -1 3 0 
0 0 -1 -1 0 3</td></tr></table>


# Constraints



# Note



# Source


