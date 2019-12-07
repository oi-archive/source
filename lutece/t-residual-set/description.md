
# Content

Given a pair of number $(p,t)$ where $p$ is a prime and $t$ is a non-negative integer.

The `Residual Set` of any prime number $p$ is all the integers between $1$ and $p-1$,

that is, $1, 2, 3, 4, \cdots, p-2, p-1$.

What's more, a `T-Residual Set` of any prime number p means the set of integers below:

$1^T\ mod\ p, 2^T\ mod\ p, 3^T\ mod\ p, 4^T\ mod\ p, \cdots (p-2)^T\ mod \ p, (p-1)^T\ mod \ p$, where $T$ must be non-negative.

Now for each pair of $(p,t)$, you should calculate how many distinct numbers there are in the `t-Residual Set` of $p$.

# Standard Input

A number $T$ ($T\leq 10^6$) in first line.

Then $T$ test cases follow.

Each Test case contains two number $p$ ($0<p<10^8$) and $t$ ($0<t<2^{31}$),

which meanings areaccording to the description.

# Standard Output

Output $T$ lines.

Each line contains one number, refers to the answer.

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
7 9
17 89
47 56</td><td>2
16
23</td></tr></table>


# Constraints



# Note



# Source


