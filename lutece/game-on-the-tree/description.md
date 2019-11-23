
# Content

Given a tree, a connected graph that contains $N$ vertices and $N-1$ edges, you should control a virtual miner to get maximum values by walking from a vertex A and stopping at a vertex B.

On a tree, as we know, there is only one road between every two vertices. Here, you are allowed to choose a vertex A (the value of A can not be 0) and a vertex B by yourself. Walking from A and stopping at B, you must collect all the values on the road. Each vertex has a value. Try to get values as large as you can. Remember that the miner you controlled, can never go back to any vertex he has passed.

However, there is a special way to calculate total values. Let’s assume that the miner has passed $M$ vertices from A to B. During the travel, the miner has successively collected $M$ values worths $Wi$ $(0 \leq i < M)$. Vertex A has a value worth $Wi$ $(i = M - 1)$. The next vertex on the road has a value worth $Wi$ $(i = M - 2)$ ...... At last, vertex B has a value worth $Wi$ $(i = 0)$. The special rule gives you an integer $P$. The total value you collect is calculated by the formula $MAX = \sum_{i = 0}^{m-1}(W_i \times P^i)$.

It is guaranteed that $Wi$ $(0 \leq i < M)$ are less than $P$. The vertex A and B you choose can be same. But the value of A can not be 0. Output $MAX$ module $(10^9 + 7)$. Note that you need to make sure $MAX$ as large as possible but $NOT$ make sure the remainder as large as possible. And then, output value of each vertex (stating from vertex A) on the road in the best case.

# Standard Input

The first line contains an integer $T (1 \leq T \leq 200)$, indicating the number of test cases.

For each case, The first and second line contain two integers $N$ $( 1 \leq N \leq 10^4 )$ and $P$ $( 2 \leq P \leq 10^9)$, indicating the number of vertices and the integer $P$.

Each of the following $N-1$ lines contains two integers $a$ and $b$ $(1 \leq a, b \leq N, a \neq b)$, indicating that there is an edge connecting vertex $a$ and vertex $b$.

The following line contains $N$ integers $Wi$ $( 0 \leq Wi < P, \sum Wi > 0)$, the value of each vertex. It is guaranteed that at least one of $Wi$ not equal 0.

You can assume that sum of $N$ does not exceed $1.3 \times 10^6$.

# Standard Output

For each case, the first line outputs "Case #$T$: $MAX$"(without quotes). Here, $T$ is the index of test case (starting from 1) and $MAX$ is the maximum value the miner can collect module $(10^9 + 7)$.

The second line outputs the value of each vertex from vertex A to vertex B.

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

8
2
1 2
2 3
3 4
4 5
2 6
6 7
7 8
1 0 0 0 0 0 0 0

9
1000000000
1 2
2 3
1 4
4 5
1 6
6 7
1 8
8 9
1 2 0 2 0 2 0 2 0</td><td>Case #1: 16
1 0 0 0 0
Case #2: 999999356
2 1 2 0</td></tr></table>


# Constraints



# Note



# Source


