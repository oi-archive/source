
# Content

六一儿童节快要到了，有爱心的方伯伯决定要给他所在城市的孩子们发放糖果。已知方伯伯的城市是有$n$个路口，这$n$个路口由$n-1$条路连在一起，任意两个路口之间有且仅有一条路径，即这$n$个路口构成一棵树。

现在方伯伯想在某些路口设立糖果发放点，使得这$n-1$条路中的任意一条路，至少有一个端点设立了糖果发放点。因为方伯伯最近刚刚赞助了某省省赛，资金周转出了一些困难，所以他希望能够设立尽量少的糖果发放点，同时也希望知道有多少方案能够使得糖果发放点的个数最少，由于方案数可能会很大，所以只需求出方案数模$10007$的数即可。

# Standard Input

第一行有一个整数$T(T \leq 12)$，代表测试数据的组数。

对于每组数据，第一行读入一个$n，2 \leq n \leq 100000$，代表树的路口个数。

接下来$n-1$行每行两个整数$u，v$，代表路口$u$和路口$v$之间存在一条路，$1 \leq u,v \leq n, u \neq v$

# Standard Output

对于每组数据，输出两个数，第一个数代表糖果发放点的个数，第二个数代表使得糖果发放点个数最少的方案数。

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
4 
1 2 
2 3 
3 4 
3 
1 2 
1 3</td><td>2 3 
1 1</td></tr></table>


# Constraints



# Note



# Source


