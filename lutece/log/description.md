
# Content

Given a number $sum(1\leq sum \leq 100000000)$,we have $m$ queries which contains a pair ($x\_i,y\_i$) and would like to know the smallest nonnegative integer $k\_{i}$ satisfying  $x\_i^{k\_{i}}=y_i\ mod\  p$ when the prime number $p\ (sum\ mod\ p = 0)$

# Standard Input

The first line contains a number T, indicating the number of test cases.  

For each case, each case contains two integers $sum,m(1\leq sum\leq 100000000,1\leq m\leq 100000)$ in the first line.  

The next $m$ lines will contains two intgeers $x\_i,y\_i(0\leq x_i,y_i\leq1000000000)$

# Standard Output

For each test case,output  "Case #$X$:"  and $m$ lines.($X$ is the case number)  

Each line cotain a integer which is the smallest integer for ($x\_i,y\_i$) ,if we can't find such a integer just output "-1" without quote.

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
175 2
2 1
2 3</td><td>Case #1:
0
3</td></tr></table>


# Constraints



# Note

$175\ =5^2*7$  

$2^0\ mod\ 5\ =\ 1$  

$2^3\ mod\ 7\ =\ 1$  

So the answer to (2,1) is 0

# Source


