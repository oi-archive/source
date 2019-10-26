
# Content

You must have ever learned fibonacci sequence, which satisfy $F_n = F_{n-1} + F_{n-2}$, we define $F_1 = 1$ and $F_2 = 2$ here.

For a postive integer $N$, consider all different integer $\alpha$ array as set $\Re$ which satisfy the following condition:
$N = \sum_{i=1}^{\infty} \alpha_i \cdot F_i(\alpha_i \geq 0)$

We define
$f(N)=\sum_{\alpha \in \Re}(\sum_{i=1}^{\infty}\alpha_i \cdot i^2)^2$

Now you are given $Q$ queries, for each query you are given a positive integer $N$, you need to print $f(N) \mod 10^9 + 7$ in a single line.

# Standard Input

The first line contains one integer $Q$ $(1 \leq Q \leq 10^5).$

Each of the next $Q$ lines contatins a postive integer $N$ $(1 \leq N \leq 10^5).$

# Standard Output

For each query, print $f(N) \mod 10^9 + 7$ in a single line.

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
2
3</td><td>1
20
115</td></tr></table>


# Constraints



# Note



# Source


