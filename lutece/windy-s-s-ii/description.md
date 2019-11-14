
# Content

Given a string $A$ with length $N$.

$A\_0, A\_1, A\_2, A\_3 \cdots A\_{N-1}$ 

$S(0) = A\_0, A\_1, A\_2, A\_3 \cdots A\_{N-2}, A\_{N-1}$ 

$S(1) = A\_1, A\_2, A\_3 \cdots A\_{N-2}, A\_{N-1}, A\_0$ 

$S(2) = A\_2, A\_3 \cdots A\_{N-2}, A\_{N-1}, A\_0, A\_1$ 

......

$S(N-1) = A\_{N-1}, A\_0, A\_1, A\_2, A\_3 \cdots A\_{N-2}$ 

Windy want to know how many $i$ in $[0, N - 1]$ that make $S(i)$ euqal to $S(0)$.

Can you find it for Windy?

# Standard Input

The first line of input is the number of test case.

For each test case,
there is only one line contains a string $A$.

String $A$ only contains lowercase letter (`a`--`z`).

$1 \leq N \leq 1000$

# Standard Output

For each test case output the answer on a single line.

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
aaa
abab
aba</td><td>3
2
1</td></tr></table>


# Constraints



# Note



# Source


