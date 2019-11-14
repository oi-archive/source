
# Content

You are given an array $A$ of size $N$, and here's an extra $B$ array of size $N$, initially, each element of the $B$ array is zero.

You need support $Q$ queries of following three types.

* $1$ $l$ $r$ $x$: Add $x$ to $A_l,A_{l+1},...,A_r$. $( 1 \leq l \leq r \leq N , 0 \leq X < 2^{32})$

* $2$ $l$ $r$ $k$ $b$: Make $B_i = B_i + k \cdot A_i + b$ for $i \subseteq [l,r]$. $( 1 \leq l \leq r \leq N , 0 \leq k,b < 2^{32})$

* $3$ $l$ $r$: Query $\sum_{i=l}^{r}B_i \mod 2^{32}$. $( 1 \leq l \leq r \leq N)$

# Standard Input

The first line contains two integers $N$ $(1 \leq N \leq 10^5)$ and $Q$ $(1 \leq Q \leq 4 \cdot 10^5)$.

The next line contains $N$ integers indicates each element of $A_i$ $( 0 \leq A_i < 2^{32})$.

Each of the next $Q$ lines contains a query in the format given in the statement.

# Standard Output

For each query of type $3$, print the corresponding answer in a single line.

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
<tr><td>6 4
7 7 2 0 0 2
3 2 4
1 2 5 4
2 2 3 7 6
3 1 5</td><td>0
131</td></tr></table>


# Constraints



# Note



# Source


