
# Content

A tree structure is very special structure, there is exactly one path connecting each pair of nodes.

Now, given a tree structure, which has $N$ nodes(conveniently labeled from $1$ to $N$). And the root of the tree is always labeled with $1$. You are to write a program to figure out that, for every node $V$ in the tree, how many nodes there are in the sub-tree rooted by $V$ and it’s label number is larger than the label number of $V$.

![title](/source/lutece/easy-tree-problem/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDU1LzIwMTQwODE4MjI1MTUwOTM0MTcuanBn.jpg)

For the example above:
* $Ans\_1 = 6, Ans\_2 = 1, Ans\_3 = 2, Ans\_4 = 0, Ans\_5 = 0, Ans\_6 = 0, Ans\_7 = 0$

# Standard Input

There are multiple cases.The first line is an integer $T$ representing the number of test cases.The following lines every tow lines representing a test case. For each case there are exactly two lines:The first line with a single integer $N$($1 \leq N \leq 200000$), representing the size of tree.The second line with $N – 1$ numbers: $P\_2, P\_3, \cdots P\_n$. ($1 \leq P\_i \leq N$),Which mean the father node of node $i$ is $P\_i$.It is guaranteed that the input data is a tree structure and has $1$ as root.

# Standard Output

For each test case, output a line of $N$ numbers in the following format:
* `Case #C: Ans[1] Ans[2] Ans[3] ... Ans[N]`

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
7
1 1 3 2 1 3
4
1 2 3</td><td>Case #1: 6 1 2 0 0 0 0
Case #2: 3 2 1 0</td></tr></table>


# Constraints



# Note



# Source


