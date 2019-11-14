
# Content

Your job is to calculate $\sum(S\_1\rm\ XOR\ S\_2\rm\ XOR \cdots XOR\ S\_n)\rm\ mod\ 1000000007$, where $L\_i\leq S\_i\leq H\_i$, $1\leq i\leq n$.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 100$), which stands for the number of test cases you need to solve.

Every test case begins with an integer $n$ ($1\leq n\leq 100$), and followed by n pairs of integers $L\_1, H\_1, L\_2, H\_2, \cdots ,L\_n, H\_n$ ($1\leq L\_i\leq H\_i\leq 10^9, 1\leq i\leq n$). Every pair occupies a line.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then output the answer. See sample for more details.

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
1
1 10
2
1 2
2 3</td><td>Case #1: 55
Case #2: 6</td></tr></table>


# Constraints



# Note

A bitwise $\rm XOR$ performs the logical $\rm XOR$ operation on each pair of corresponding bits. The result in each position is $1$ if the two bits are different, and $0$ if they are the same. For example: `0101`(decimal $5$)$\rm\ XOR\ $`0011`(decimal $3$) $=$ `0110`(decimal $6$).

# Source


