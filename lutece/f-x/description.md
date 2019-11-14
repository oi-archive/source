
# Content

For a decimal number $x$ with $n$ digits ($A\_{n}A\_{n-1}A\_{n-2}\cdots A\_{2}A\_{1}$), we define
its weight as $F(x)=A\_{n}\times 2^{n-1}+A\_{n-1}\times 2^{n-2}+\cdots +A\_{2}\times 2+A\_{1}\times 1$.
Now you are given two numbers $A$ and $B$, please calculate how many numbers are there
between $0$ and $B$, inclusive, whose weight is no more than $F(A)$.

# Standard Input

The first line has a number $T$ ($T\leq 10000$) , indicating the number of test cases.

For each test case, there are two numbers $A$ and $B$ ($0\leq A,B<10^9$)

# Standard Output

For every case,you should output `Case #t: ` at first, without quotes. 
The $t$ is the case number starting from $1$.
Then output the answer.

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
0 100
1 10
5 100</td><td>Case #1: 1
Case #2: 2
Case #3: 13</td></tr></table>


# Constraints



# Note



# Source


