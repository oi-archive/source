
# Content

As we know, Bi Luo is a magic boy, he always has some excited questions , now a new question comes.

You are given a simple undircted graph( graph in which both multiple edges and loops are disallowed ) $G$ with $N$ vertexs and $M$ edges, Bi Luo wants you tu caculate the excited value of $G$,the caculating processing are as follows.

At the begining, the excited value is $0$. then for each non-empty subset of edge $M$ , we just think its edge-induced subgraph, we define it as $G^{\ast}$, if all of the vertexs within $G^{\ast}$ are in a single connected block and the number of edges in $G^{\ast}$ equal to the number of vertexs  $G^{\ast}$ ,  it makes excited value ++ , otherwise do nothing.
Now, Bi Luo wants to know the excited value of $G$, can you answer it?

# Standard Input

First Line is an positive integer $T$ , ( $1 \leq T \leq 10$ ) , represents there are $T$ test cases.

For each test case: 

The first line contains two positive integers $N$ , $M$.( $1 \leq N\leq 12$ , $0 \leq M \leq \frac{N*(N-1)}{2}  $ ) . represents there are $N$ vertexs and $M$ edges.

The next $M$ line, each line contains two integers $u$ , $v$( $1 \leq u , v  \leq N $) , indicating there is an edge between $u$ and $v$.

You may assume that the given graph $G$ is always a simple graph and there are no more than two test cases with $N = 12$ ,no more than two test cases with $N = 11$.

# Standard Output

For tht $i$-$th$ test case , first output Case #i:  ,then output one integer repretens the excited value,because the excited value may be large, so you only need to output the excited value of $G$ mod $10^9+7$

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
1 2
1 3
2 3
5 5
1 2
1 3
2 3
2 4
3 5
</td><td>Case #1: 1
Case #2: 4
</td></tr></table>


# Constraints



# Note



# Source


