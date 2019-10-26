
# Content

Given a connected undirected graph, tell if its minimum spanning tree is unique.

#####Definition $1$ (Spanning Tree): 

Consider a connected, undirected graph $G = (V, E)$. A spanning tree of $G$ is a subgraph of $G$, say $T = (V', E')$, with the following properties:
1.  $V' = V$.
2.  $T$ is connected and acyclic.

#####Definition $2$ (Minimum Spanning Tree): 

Consider an edge-weighted, connected, undirected graph $G = (V, E)$. The minimum spanning tree $T = (V, E')$ of $G$ is the spanning tree that has the smallest total cost. The total cost of $T$ means the sum of the weights on all the edges in $E'$.

# Standard Input

The first line contains a single integer $t (1 \leq t \leq 100)$, the number of test cases. Each case represents a graph. It begins with a line containing two integers $n$ and $m (1 \leq n \leq 100)$, the number of nodes and edges. Each of the following m lines contains a triple $(x\_i, y\_i, w\_i)$, indicating that $x\_i$ and $y\_i$ are connected by an edge with weight = $w\_i. (1 \leq x\_i \leq n,1 \leq yi \leq n,x\_i ≠ y\_i,0 \leq w\_i \leq 10000)$.For any two nodes, there is at most one edge connecting them.

# Standard Output

For each input, if the MST is unique, print the total cost of it, or otherwise print the string `Not Unique!`

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
3 3
1 2 1
2 3 2
3 1 3
4 4
1 2 2
2 3 2
3 4 2
4 1 2</td><td>3
Not Unique!</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by Nilil. So any mistake here does not imply mistake in the offcial judge data.

# Source


