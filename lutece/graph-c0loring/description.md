
# Content

In computational complexity theory, a problem is NP-complete when it is both in NP and NP-hard.

The set of NP-complete problems is often denoted by **NP-C** or **NPC**. The abbreviation NP refers to ``nondeterministic polynomial time''.

It seems that you need to solve a NP-complete problem now.

There is a simple undirected graph composed by $N$ vertices and $M$ edges, and the vertices are labeled from $1$ to $N$.

You need to color each vertex by a specific color such that there are no edges connect two vertices which have the same color.

Calculating the minimum number of colors you need to use.

# Standard Input

The first line contains two integers $N$ and $M$.

For the next $M$ lines, each line contains two integer $u$ and $v$, denotes an edge between the $u\_{th}$ vertex and the $v\_{th}$ vertex.

$1 \leq N \leq 23$, $0 \leq M \leq \frac{N(N - 1)}{2}$, $1 \leq u, v \leq N$.

# Standard Output

The minimum number of colors you need to use.

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
<tr><td>4 6
1 2
1 3
1 4
2 3
2 4
3 4</td><td>4</td></tr></table>


# Constraints



# Note



# Source


