
# Content

In mathematics, especially in combinatorics, Stirling numbers of the first kind arise in the study of permutations. In particular, the Stirling numbers of the first kind count permutations according to their number of cycles (counting fixed points as cycles of length one).

 $S(n,k)$ count the number of permutations of $n$ elements with $k$ disjoint cycles.

 We have the recurrence relation:

 $$S(n + 1, k) = n \cdot S(n, k) + S(n, k - 1). \ k \geq 1 $$

With the initial conditions: $S(0,0)=1\ and\ S(n,0)=S(0,n)=0$.

Now Bob has a problem:

Given a prime $P$ and two integers $x$ and $n$, he wants to calculate the number of $m$ between $0$ and $n$ such that $ S(n,m) \equiv x$ $(\mod \ P\ )$.

# Standard Input

There are two integers $n$ and prime $P$ in the first line. ($1 \leq n \leq 10^{15},2 \leq P \leq 10^5$)

The next line contains number of questions $Q$. $(1 \leq Q \leq 10^5)$

Each question contains an integer $x$. ($0 \leq x < P$)

# Standard Output

For each query print the corresponding answer in a single line.

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
<tr><td>32 17
17
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16</td><td>5
2
2
4
0
2
0
2
2
2
2
0
2
0
4
2
2</td></tr></table>


# Constraints



# Note



# Source


