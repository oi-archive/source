
# Content

There is a rooted tree with $n$ vertices. That is, there are exactly $n - 1$ edges and it is possible to go from any vertice to any other vertice by following some sequence of edges.  The tree are numbered from $1$ to $n$, and the root is $1$. Every vertice has a colour in the range of $[1, n]$. 
There are $m$ operations on the tree.
```
0 v c : make the colour of the vertice v be c.
1 v : query the number of different colours in the subtree rooted at vertice v.
```

# Standard Input

The first line contains a single integer $n$.

Each of the following $n - 1$ lines contains $2$ integers $a\_i$ and $b\_i$, which denotes an edge between $a\_i$ and $b\_i$.

There are $n$ integers in the following line. The $i\_{th}$ integer $c\_i$ denotes the initial colour of the vertice numbered $i$.

The following line contains a single integer $m$, the number of the oprations in the following.

Then $m$ lines follow, each gives an operation. Each operation belongs to either kind:
```
0 v c : make the colour of the vertice v be c.
1 v : query the number of different colours in the subtree rooted at vertice v.
```
We guarantee that the vertices form a rooted tree and the root is at $1$.

$1 \leq n, m \leq 100000, 1 \leq a\_i, b\_i, c\_i, v, c \leq n$

# Standard Output

For each $1$ $v$ opration, print the answer in a single line.

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
1 2
1 3
2 5
2 4
1 2 3 4 5
6
1 1
0 4 2
1 1
1 2
0 2 3
1 2</td><td>5
4
2
3</td></tr></table>


# Constraints



# Note



# Source


