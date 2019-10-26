
# Content

The Farey Sequence $F_n$ for any integer $n$ with $n \geq 2$ is the set of irreducible rational numbers $\frac{a}{b}$ with $0 < a < b \leq n$ and $\gcd(a,b) = 1$ arranged in increasing order. 

The first few are:

* $F_2 = [\frac{1}{2}]$ 
* $F_3 = [\frac{1}{3}, \frac{1}{2}, \frac{2}{3}]$ 
* $F_4 = [\frac{1}{4}, \frac{1}{3}, \frac{1}{2}, \frac{2}{3}, \frac{3}{4}]$ 
* $F_5 = [\frac{1}{5}, \frac{1}{4}, \frac{1}{3}, \frac{2}{5}, \frac{1}{2}, \frac{3}{5}, \frac{2}{3}, \frac{3}{4}, \frac{4}{5}]$

Now, your task is to print Farey Sequence given the value of $n$.

# Standard Input

There are several test cases. The first line is an integer giving the number of cases. Each test case has only one line, which contains a positive integer $n$ 
($2 \leq n \leq 3000$).

# Standard Output

For each test case, you should output one line, which contains the corresponding Farey Sequence. Adjacent terms are separated by a single `,` and there can't be any white spaces in your output. See Sample Output for more clarifications on the output format.

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
<tr><td>4
2
3
4
5</td><td>1/2
1/3,1/2,2/3
1/4,1/3,1/2,2/3,3/4
1/5,1/4,1/3,2/5,1/2,3/5,2/3,3/4,4/5</td></tr></table>


# Constraints



# Note

Do Not use cout to produce the output for this problem, since it is inefficient.

# Source


