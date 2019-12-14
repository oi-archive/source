
# Content

As we know, Bi Luo is a magic boy, he always has some excited questions , now a new question comes.

You are given a simple unrooted tree $G$ , Bi Luo wants you to caculate the excited value of the $G$.

At the begining , excited value is $0$ ,  then for each non-empty subset of $N$ , we just think its vertex-induced subgraph $G^{\ast}$ , then we think each non-empty subset of $N$ again, we just think its vertex-induced subgraph $G^{\ast\ast}$ , if $G^{\ast\ast}$ is a connected graph and $G^{\ast\ast}$ completely contained $G^{\ast}$ , then excited value adds $zhu$[the number of vertexs in $G^{\ast\ast}$] , otherwise do nothing.

Now, Bi Luo wants you to caculate the excited value of $G$, can you help him?

# Standard Input

First Line is an positive integer $T$ , ( $1 \leq T \leq 100$ ) , represents there are $T$ test cases.

For each test case: 

The first line contains two positive integers $N$ .( $1 \leq N\leq 2000$  ) . represents there are $N$ vertexs.

The next $N-1$ line, each line contains two integers $u$ , $v$( $1 \leq u , v  \leq N$) , indicating there is an edge between $u$ and $v$.

The next line contains $N$ integers , represents the elements of $zhu[i]$.( $1 \leq zhu[i]  \leq 10^9$) 

You may assume that there are no more than $25$ test cases with $1000 < N  \leq 2000$ .

# Standard Output

For tht $i$-$th$ test case , first output Case #i:  ,then output one integer repretens the excited value,because the excited value may be large, so you only need to output the excited value of $G$ mod $152076289$

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
1
1
2
1 2
1 1
3
1 2
2 3
1 1 1</td><td>Case #1: 1
Case #2: 5
Case #3: 16
</td></tr></table>


# Constraints



# Note



# Source


