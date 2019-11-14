
# Content

Given a nonnegative integer $a$, and a positive integer $N$, we define:

$f(a, 1) = a$ 

$f(a, k) = f(a, k – 1) \times f(a, k – 1)\mod{N}, k > 1$

There may or may not exist some positive integer $k$ satisfying $f(a, k) = 0$.

Your task is, given a positive integer $N$, to determine how many $a (0 ≤ a ≤ N)$ there are, such that for some positive integer $k$, $f(a, k) = 0$.

# Standard Input

The input contains an integer $T$ on the first line, indicating the number of test cases. Each test case contains only one positive integer $N$ ($1 \leq N \leq 1000000000$) on a line.

# Standard Output

For each test case, output the answer on a single line.

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
<tr><td>6
2
12
50
180
245
361</td><td>2
3
6
7
8
20</td></tr></table>


# Constraints



# Note



# Source


