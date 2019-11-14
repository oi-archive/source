
# Content

Alice is given a tree, in which each edge has a length and each node has a color either white or black. A tree is a graph in which there are exactly $n - 1$ edges and it is possible to go from any node to any other node by following some sequence of edges. 

For convenience, the edges are labeled from $1$ to $n - 1$, and the nodes are labeled from $1$ to $n$.

Now Alice is asked to make $m$ operations on the tree. There are three different kinds of operations.
```
0 k x : change the length of the k-th edge to x.
1 u : change the color of node u.
2 u : query the minimum distance between node u and a black node.
```
As is known to everyone of you, Bob loves Alice very much. Could you tell Bob the answers to help Bob leave a good impression on Alice.

# Standard Input

The first line contains a single integer $n$, indicating the number of nodes in the tree.

There are $n$ integers in the second line. The $i\_{th}$ integer $c\_i$ denotes the initial colour of the node $i$. $0$ is white, and $1$ is black.

Each of the following $n - 1$ lines contains $3$ integers $a\_i, b\_i$ and $c\_i$, which denotes an edge between $a\_i$ and $b\_i$, and the length is $c\_i$.

The following line contains a single integer $m$, indicating the number of operations.

Then $m$ lines is following. There are three different kinds of operations.
```
0 k x : change the length of the k-th edge to x.
1 u : change the color of node u.
2 u : query the minimum distance between node u and a black node.
```
It is guaranteed that $1 \leq n, m \leq 100000, 1 \leq k < n, 1 \leq x \leq 10000, 1 \leq u \leq n$.

# Standard Output

For each query operation $2$ $u$, output the answer in one line. 

Note that : if $u$ is a black node, the answer is $0$. if there is no black node in the tree, print `-1` instead.

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
<tr><td>5
1 0 1 0 1
1 2 3 
1 3 4
2 4 5
2 5 6
9
2 2
2 4
1 1
2 4
0 2 10
2 1
1 5
1 3
2 1</td><td>3
8
11
9
-1</td></tr></table>


# Constraints



# Note



# Source


