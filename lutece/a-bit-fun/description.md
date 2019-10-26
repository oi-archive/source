
# Content

There are $n$ numbers in a array, as $a\_{0},a\_{1}\cdots ,a\_{n-1}$, and another number $m$. We define a function $f(i,j)=a\_{i}|a\_{i+1}|a\_{i+2}|\cdots |a\_{j}$. Where $|$ is the bit-OR operation. ($i\leq j$)

The problem is really simple: please count the number of different pairs of ($i,j$) where $f(i,j)<m$.

# Standard Input

The first line has a number $T$ ($T\leq 50$) , indicating the number of test cases.

For each test case, first line contains two numbers $n$ and $m$.($1\leq n\leq 100000, 1\leq m\leq 2^{30}$) Then $n$ numbers come in the second line which is the array a, where $1\leq a_{i}\leq 2^{30}$.

# Standard Output

For every case, you should output `Case #t: ` at first, without quotes. The $t$ is the case number starting from $1$.

Then follows the answer.

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
3 6
1 3 5
2 4
5 4</td><td>Case #1: 4
Case #2: 0</td></tr></table>


# Constraints



# Note



# Source


