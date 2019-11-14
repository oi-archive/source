
# Content

&ensp;&ensp;&ensp;&ensp;一直追寻着$Amorphous$的$Cocona$掉到了一个前所未见的空间里，这个空间是一片广袤的森林，其中多棵巨大的紫色的树引起了他们的注意。
<center> ![title](/source/lutece/pure-forest/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTcwMC8yMDE3MDYwNDIwNDcyMjQwOTIzLmdpZg==.gif)</center >


&ensp;&ensp;&ensp;&ensp;博士告知他们$Amorphous$就藏在这些紫色的树中间，当最后一棵紫树被砍倒后，$Amorphous$就会显露出来。然而，与此同时，$Yayaka$也在寻找着这枚$Amorphous$，
一场争斗不可避免地发生了。为了获得$Amorphous$，$Cocona$和$Yayaka$会轮流地砍断一根树枝，当某个人砍断最后一根树枝时，她就获得了胜利。

&ensp;&ensp;&ensp;&ensp;每棵紫树都会被用一些节点和边表示出来，每一个非根节点都会有一条路径连至一个根节点，当一条边被砍断，所有脱离根节点的节点及它们之间的边都会消失。这些树保证不会成环。

&ensp;&ensp;&ensp;&ensp;现在，共有$N$个节点，$Cocona$首先开始砍树。若$Cocona$和$Yayaka$都采取最优的策略，$Cocona$能获得$Amorphous$吗？

# Standard Input

第一行输入一个$N$，节点数 $(1<=N<=1000)$

第二行共有$N$个数，$fa[i]$表示第$i$个节点的父节点，若$f[i]==-1$,表示节点$i$是一个根节点。$（0<=i<=n-1）$

# Standard Output

若$Cocona$能获得$Amorphous$，输出一行$YES$，否则输出$NO$

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
<tr><td>8
-1 1 2 2 -1 5 6 6</td><td>NO</td></tr></table>


# Constraints



# Note



# Source


