
# Content

You are given an array $A$ of $N$ non-negative integers and an integer $M$.

Find the number of pair$(i,j)$ such that $1 \leq i \leq j \leq N$ and $\min(A_i,A_{i+1},...,A_j) \cdot (A_i \oplus A_{i+1} \oplus ... \oplus A_j ) \leq M$.

# Standard Input

The first line contains two integers $N$ $(1 \leq N \leq 10^5)$ and $M$ $(0 \leq M \leq 10^{18})$.

The second line contains $N$ integers representing the elements of $A_i$ $(1 \leq A_i \leq 10^9)$.

# Standard Output

Print the corresponding answer in a single line.

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
<tr><td>4 2
1 4 772002 200277</td><td>1</td></tr><tr><td>5 3
1 2 3 2 1</td><td>11</td></tr></table>


# Constraints



# Note



# Source


