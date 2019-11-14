
# Content

Given a set of $n$ integers: $num=\\{num\_1，num\_2，\cdots ,num\_n\\}$ and an integer $m$.

we define a function $AA(num,m)$ as below: 

$AA(num,m)=\\{[l,r]\mid (l\leq r)\ and\ (num\_l\ xor\ num\_{l+1}\cdots\ xor\ num\_{r})\leq m \\}$.

Your task is to calculate the number of element of $AA(num,m)$.

# Standard Input

The first line contains the number of test cases.

For every test,the input consists of two lines.

The first line contains two integers $n$ and $m$.
 
There are $n$ integers in the second line.

limit: $1\leq n\leq 10^5$, $0\leq num\_i$, $m<2^{31}$;

# Standard Output

For each test case just output one integer in one line.

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
2 3
1 4
2 3
4 5</td><td>1
1</td></tr></table>


# Constraints



# Note



# Source


