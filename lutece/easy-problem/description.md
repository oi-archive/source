
# Content

There are some positive integer numbers, and you want to divide them into two nonempty sets (every integer should be in and only in one set) and get a value descripted below:

Assume that set $A$ has $n\_1$ numbers $A\_1, A\_2, \cdots ,A\_{n\_1}$; set $B$ has $n\_2$ numbers $B\_1, B\_2, \cdots ,B\_{n\_2}$.
Let

$$v\_1=\sum\_{i=1}^{n\_1}\frac{A\_i}{n\_1}$$
$$v\_2=\sum\_{i=1}^{n\_2}\frac{B\_i}{n\_2}$$

Then

$$ans=\sum\_{i=1}^{n\_1}(A\_i-v\_2)^2+\sum\_{i=1}^{n\_2}(B\_i-v\_1)^2$$

We want to know the largest ans.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 20$), which stands for the number of test cases you need to solve.

Every test case begins with an integer $N$ ($2\leq N\leq 1000$), then followed by $N$ positive integers on the next line, these numbers will not exceed $1000$.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then output the answer rounded to six digits after the decimal point. See sample for more details.

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
3
1 1 1
3
1 2 3</td><td>Case #1: 0.000000
Case #2: 7.250000</td></tr></table>


# Constraints



# Note



# Source


