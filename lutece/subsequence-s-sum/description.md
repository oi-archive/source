
# Content

Given a sequence, you should calculate there are how many subsequence that sum of every number of the subsequence is less than a given number $K$.

# Standard Input

First a number $T$ ($T\leq 20$) indicates the test cases. Then $T$ test cases followed.

Every case are six integers $N$, $A$, $B$, $C$, $M$, $K$, where $N$ is the size of the sequence, and $K$ is mentioned above.

$A$, $B$, $C$ is described the sequence. If the sequence is $S\_1, S\_2, \cdots S\_N$, then $S\_1 = A$, $S\_2 = B$, $S\_i = ((S\_i-1) \times (S\_i-2) + C)\mod M$, $3\leq i\leq N$.

$1\leq N\leq 10^6$, $0\leq A, B, C < M\leq 10^9$, $0\leq K\leq 10^9$.

# Standard Output

For each test case, output one line. First ,output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then, output the answer.

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
<tr><td>1
5 4 7 0 11 19</td><td>Case #1: 9</td></tr></table>


# Constraints



# Note

The sequence is `4 7 6 9 10`, so there are $9$ subsequence's sum less than $19$.

The subsequence should be continuous and contain at least one number.

# Source


