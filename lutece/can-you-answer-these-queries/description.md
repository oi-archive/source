
# Content

You are given two functions $F(n)$ and $G(n)$, and these two functions will defined as:

$F(0) = a, F(1) = b, G(0) = c, G(1) = d$

and for $n >= 2$, $F(n) = G(n - 1) + G(n - 2), G(n) = F(n - 1) + F(n - 2)$.

A query is defined as follows: 

Query($n$) = $\left(F(n) \times G(n)\right) \text{ mod } P$, here $P = 10^9 + 9$.

Given $M$ queries, your program must output the results of these queries.

# Standard Input

The first line of the input file contains the integer $M (1 \leq M \leq 10000)$.

$M$ lines follow, where line $i$ contains $5$ numbers $a_i$, $b_i$, $c_i$, $d_i$ and $n_i$($-10^{18} \leq a_i, b_i, c_i, d_i \leq 10^{18}$ and $0 \leq n \leq 10^{18}$).

# Standard Output

Your program should output the results of the $M$ queries, one query per line.

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
<tr><td>4
0 1 0 1 0
0 1 0 1 1
0 1 0 1 3
0 1 0 1 4
</td><td>0
1
4
9
</td></tr></table>


# Constraints



# Note



# Source


