
# Content

Given an undirected weighted graph $G$, you should find one of spanning trees specified as follows.

The graph $G$ is an ordered pair $(V, E)$, where $V$ is a set of vertices {$v\_1, v\_2, \cdots , v\_n$} and $E$ is a set of undirected edges {$e\_1, e\_2, \cdots , e\_m$}. Each edge $e ∈ E$ has its weight $w(e)$.

A spanning tree $T$ is a tree (a connected subgraph without cycles) which connects all the $n$ vertices with $n - 1$ edges. The slimness of a spanning tree $T$ is defined as the difference between the largest weight and the smallest weight among the $n - 1$ edges of $T$.

![title](/source/lutece/slim-span/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjYzLzIwMTQwMzE4MjAzNTQ0MDE0MjMucG5n.png)

*Figure 5: A graph G and the weights of the edges*

For example, a graph $G$ in Figure 5(a) has four vertices {$v\_1, v\_2, v\_3, v\_4$} and five undirected edges {$e\_1, e\_2, e\_3, e\_4, e\_5$}. The weights of the edges are $w(e\_1) = 3, w(e\_2) = 5, w(e\_3) = 6, w(e\_4) = 6, w(e\_5) = 7$ as shown in Figure $5(b)$.

![title](/source/lutece/slim-span/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjYzLzIwMTQwMzE4MjAzNzA5MDg2MjQucG5n.png)

*Figure 6: Examples of the spanning trees of G*

There are several spanning trees for $G$. Four of them are depicted in Figure $6(a)~(d)$. The spanning tree $Ta$ in Figure $6(a)$ has three edges whose weights are $3, 6$ and $7$. The largest weight is $7$ and the smallest weight is $3$ so that the slimness of the tree $Ta$ is $4$. The slimnesses of spanning trees $Tb, Tc$ and $Td$ shown in Figure $6(b), (c)$ and $(d)$ are $3, 2$ and $1$, respectively. You can easily see the slimness of any other spanning tree is greater than or equal to $1$, thus the spanning tree $Td$ in Figure $6(d)$ is one of the slimmest spanning trees whose slimness is $1$.

Your job is to write a program that computes the smallest slimness.

# Standard Input

The input consists of multiple datasets, followed by a line containing two zeros separated by a space. Each dataset has the following format.

$n$ $m$ 

$a\_1$ $b\_1$ $w\_1$ 

$ \cdots $ 

$a\_m b\_m w\_m$ 

Every input item in a dataset is a non-negative integer. Items in a line are separated by a space. $n$ is the number of the vertices and m the number of the edges. You can assume $2 \leq n \leq 100$ and $0 \leq m \leq \frac{n \times (n-1)}{2}$. $a\_k$ and $b\_k (k = 1, \cdots, m)$ are positive integers less than or equal to $n$, which represent the two vertices $v\_{a\_k}$ and $v\_{b\_k}$ connected by the $k$_th edge $e\_k$. $w\_k$ is a positive integer less than or equal to $10000$, which indicates the weight of $e\_k$. You can assume that the graph $G = (V, E)$ is simple, that is, there are no self-loops (that connect the same vertex) nor parallel edges (that are two or more edges whose both ends are the same two vertices).

# Standard Output

For each dataset, if the graph has spanning trees, the smallest slimness among them should be printed. Otherwise, `-1` should be printed. An output should not contain extra characters.

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
<tr><td>4 5
1 2 3
1 3 5
1 4 6
2 4 6
3 4 7
4 6
1 2 10
1 3 100
1 4 90
2 3 20
2 4 80
3 4 40
2 1
1 2 1
3 0
3 1
1 2 1
3 3
1 2 2
2 3 5
1 3 6
5 10
1 2 110
1 3 120
1 4 130
1 5 120
2 3 110
2 4 120
2 5 130
3 4 120
3 5 110
4 5 120
5 10
1 2 9384
1 3 887
1 4 2778
1 5 6916
2 3 7794
2 4 8336
2 5 5387
3 4 493
3 5 6650
4 5 1422
5 8
1 2 1
2 3 100
3 4 100
4 5 100
1 5 50
2 5 50
3 5 50
4 1 150
0 0</td><td>1
20
0
-1
-1
1
0
1686
50</td></tr></table>


# Constraints



# Note



# Source


