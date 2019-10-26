
# Content

This is a very easy problem, your task is just calculate el camino más corto en un gráfico, and just sólo hay que cambiar un poco el algoritmo. If you do not understand a word of this paragraph, just move on.

The Nya graph is an undirected graph with `layers`. Each node in the graph belongs to a layer, there are $N$ nodes in total.

You can move from any node in layer $x$ to any node in layer $x+1$, with cost $C$, since the roads are bi-directional, moving from layer $x+1$ to layer $x$ is also allowed with the same cost.

Besides, there are $M$ extra edges, each connecting a pair of node $u$ and $v$, with cost $w$.

Help us calculate the shortest path from node $1$ to node $N$.

# Standard Input

The first line has a number $T$ ($T\leq 20$) , indicating the number of test cases.

For each test case, first line has three numbers $N$, $M$ ($0 \leq N$, $M \leq 10^5$) and $C$($1 \leq C \leq 10^3$), which is the number of nodes, the number of extra edges and cost of moving between adjacent layers.

The second line has $N$ numbers $l\_i$ ($1 \leq l\_i \leq N$), which is the layer of $i^{th}$ node belong to.

Then come $N$ lines each with $3$ numbers, $u$, $v$ ($1 \leq u$, $v \leq N$, $u \neq v$) and $w$ ($1 \leq w \leq 10^4$), which means there is an extra edge, connecting a pair of node $u$ and $v$, with cost $w$.

# Standard Output

For test case $X$, output `Case #X: ` first, then output the minimum cost moving from node $1$ to node $N$.

If there are no solutions, output $-1$.

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
3 3 3
1 3 2
1 2 1
2 3 1
1 3 3

3 3 3
1 3 2
1 2 2
2 3 2
1 3 4</td><td>Case #1: 2
Case #2: 3</td></tr></table>


# Constraints



# Note



# Source


