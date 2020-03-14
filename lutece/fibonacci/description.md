
# Content

In the Fibonacci integer sequence, $F\_0 = 0, F\_1 = 1,$ and $F\_n = F\_{n-1} + F\_{n-2}$ for $n \geq 2$. For example, the first ten terms of the Fibonacci sequence are:

$0, 1, 1, 2, 3, 5, 8, 13, 21, 34, \cdots$

An alternative formula for the Fibonacci sequence is

![title](/source/lutece/fibonacci/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjc4LzIwMTQwMzE5MDAyNjMyMjc1NC5wbmc=.png)

Given an integer $n$, your goal is to compute the last $4$ digits of $F\_n$.

# Standard Input

The input test file will contain multiple test cases. Each test case consists of a single line containing $n$ (where $0 \leq n \leq 1,000,000,000$). 

The end-of-file is denoted by a single line containing the number `-1`.

# Standard Output

For each test case, print the last four digits of $F\_n$. If the last four digits of $F\_n$ are all zeros, print `0`; otherwise, omit any leading zeros (i.e., print $F\_n$ mod $10000$).

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
<tr><td>0
9
999999999
1000000000
-1</td><td>0
34
626
6875</td></tr></table>


# Constraints



# Note

As a reminder, matrix multiplication is associative, and the product of two $2 \times 2$ matrices is given by

![title](/source/lutece/fibonacci/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjc4LzIwMTQwMzE5MDAyODU3Mzk0NS5wbmc=.png)

Also, note that raising any $2 \times 2$ matrix to the 0th power gives the identity matrix:

![title](/source/lutece/fibonacci/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjc4LzIwMTQwMzE5MDAyOTE2ODMxNi5wbmc=.png)

The data used in this problem is unofficial data prepared by 695375900. So any mistake here does not imply mistake in the offcial judge data.

# Source


