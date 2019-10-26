
# Content

Given a directed weighted graph who has at least three nodes, can you find the minimal directed weighted cycle with at least three nodes?

# Standard Input

The input contains a single test case.

In the first line there is two integer $n$ - the number of nodes in the graph, $m$ - the number of directed edges in the graph. $(0 < n \leq 100, 0 \leq m \leq n^2)$

Then $m$ lines follow, each line contains three integers $i$ $j$ $k$, which means that there is a directed edge coming from node $i$ to node $j$ with a weight of $k (0 \leq k < 2^{15})$.

# Standard Output

You should output a single line with a single integer presenting the weight of the cycle you have found or `-1` (without quotes) if there isn't any.

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
<tr><td>5 7
4 0 19
0 3 20
4 3 50
2 3 1
3 1 10
1 4 2
1 2 39</td><td>50</td></tr></table>


# Constraints



# Note



# Source


