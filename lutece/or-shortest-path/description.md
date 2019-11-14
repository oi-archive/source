
# Content

OR is a kind of bitwise operator, we defined that as follow: for two number $A$ and $B$ in binary notation, let $C=A\ OR\ B$. Then for each bit of $C$, we can get its value by check the digit of corresponding position in $A$ and $B$. For each digit, $1\ OR\ 1 = 1$, $1\ OR\ 0 = 1$, $0\ OR\ 1 = 1$, $0\ OR\ 0 = 0$. And we simply write this operator as $|$, like $2 | 1 = 3$,$2 | 3 = 3$.

In bitland there is a strange method to calculate the length of a path using OR. If there are $M$ edges in a path, and the length of them are $l\_1,l\_2,\cdots ,l\_M$, then the length of this path is $l\_1|l\_2|\cdots |l\_M$. Now give you a undirected graph with $N$ nodes and $M$ edges, find the OR shortest path between $S$ and $T$. If $S$ and $T$ are disconnect, we consider the length between them is $-1$.

# Standard Input

First line of the input is a single integer $T$($T\leq 30$), indicates there are $T$ test cases.

For each test case, the first line is four integers $N$($2\leq n\leq 10000$), $M$($1\leq m\leq 100000$), $S$, $T$($1\leq S,T\leq N$,$S\neq T$), indicates the number of nodes, the number of egdes, the starting node and the target node respectively. Following $M$ lines, each line contains three integers $a, b, c$($1\leq a,b\leq n$,$a\neq b$,$0\leq c<2^{30}$), means there exist an undirected edge between node $a$ and node $b$, and the length is $c$.

# Standard Output

For each test case, output one line. First ,output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then, you should output a single line contains a single number means the length of the OR shortest path between $S$ and $T$ or $-1$.

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
<tr><td>3
4 4 1 4
1 2 1
1 3 2
2 4 2
3 4 1
4 4 1 4
1 2 6
1 3 2
2 4 2
3 4 5
4 2 1 4
1 2 4
3 4 5</td><td>Case #1: 3
Case #2: 6
Case #3: -1</td></tr></table>


# Constraints



# Note

For the second case, we choose the path: $1\rightarrow 2\rightarrow 4$.

# Source


