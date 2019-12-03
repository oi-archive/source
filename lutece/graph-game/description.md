
# Content

Alice and Bob are playing a graph game, this game goes like this: Two players start the game with a graph.
They delete a edge from the graph in turn, every time the edge they deleted must be a valid edge, a edge
called valid if the sum of the degree of the two nodes it connect is even. The player who can't find a valid
edge to delete lose.

Now, They have a graph with $N$ nodes and $M$ edges, They want to play multiple times game, so each time they
choose a subgraph and playing the graph game. A subgraph is define as follow: select some nodes(maybe all) in the
original graph, and select edges which the two nodes it connect has being selected. The graph contain those
selected nodes and edges called a subgraph.

Alice will make the first deleting, now, she want to know if both players always take the best moves and never
make mistakes, how many subgraphs she will win, plaese help her.


# Standard Input

First line of the input is a single integer $T$($1\leq T \leq 20$), indicates there are $T$ test cases.

For each test case, the first line contain two integers $N$($2 \leq N \leq 40$) and $M$($1 \leq M \leq 400$),
indicating the number of nodes and edges in graph. Then $M$ lines followed, each line contains two numbers $x$ and
$y$($1 \leq x,y \leq N$), indicating there is one edge between node $x$ and node $y$, data will contain no self-loop,
and no more than one edge between any two nodes.

# Standard Output

For each case,output `Case #t: ret` in a single line, where $t$ indicates the case number between $1$ and $T$, and
$ret$ is the number of subgraphs which first player can win.

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
2 1
1 2
3 2
1 2
2 3</td><td>Case #1: 1
Case #2: 2</td></tr></table>


# Constraints



# Note



# Source


