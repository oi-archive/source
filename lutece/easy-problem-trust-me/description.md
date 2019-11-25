
# Content

Given a Directed acyclic graph (DAG) with $N$ ($1 \leq N \leq 20$) nodes and $M$ edges.

There is a set $S$ which contains $K$ ($1 \leq K \leq 10^9$) distinct integers. Each node has a set that contains some distinct integers (possibly empty).

The Directed acyclic graph is legal only if the set of each node is a subset of $S$ and is a subset of nodes which can directly arrive it.

You are supposed to calculate how many kinds of graphs are legal. Calculate the answer mod $10^9+7$.

Two graphs are considered different if there is at least one node in two graphs has different set.

`See Hint for more understanding.`

# Standard Input

The first line contains three integers $N$ ($1 \leq N \leq 20$) and $M$, $K$ ($1 \leq K \leq 10^9$).

The second $M$ lines contains two integers $a$ and $b$ ($1 \leq a , b \leq N$), representing that there is a direct edge from $a$ to $b$

It is guaranteed that the given graph is a simple graph without multiple edges.

# Standard Output

Output the answer mod $10^9+7$.

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
<tr><td>4 4 2
1 2
2 3
1 3
3 4</td><td>25</td></tr></table>


# Constraints



# Note

`Let consider the following sample.`

There are 2 nodes and 1 edges that is 1--->2. And $K$=2, that means $S$ contains 2 integers.

the set of node 2 must be a subset of node 1.

the set of node1 must be a subset of node $S$

if S={1, 2}, then , let S1 be the set of node 1, S2 be the set of node2

S1={1 ,2}  S2={1, 2}

S1={1 ,2}  S2={ 1 }

S1={1 ,2}  S2={ 2 }

S1={1 ,2}  S2={ }

S1={ 1 }  S2={ 1 }

S1={ 1 }  S2={  }

S1={ 2 }  S2={ 2 }

S1={ 2 }  S2={ 0 }

S1={  }  S2={  }

Therefore ,the answer is 9. There are 9 legal DAGs.

# Source


