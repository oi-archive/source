
# Content

The number $729$ can be written as a power in several ways: $3^6$, $9^3$ and $27^2$. It can be written as $729^1$, of course, but that does not count as a power.
We want to go some steps further. To do so, it is convenient to use `^` for exponentiation, so we define $a\verb|^|b = a^b$.
The number $256$ then can be also written as `2^2^3`, or as `4^2^2`. 
Recall that `^` is right associative, so `2^2^3` means `2^(2^3)`.

We define a *tower of powers* of *height* $k$ to be an expression of the form $a\_1\verb|^|a\_2\verb|^|a\_3\verb|^|\ldots \verb|^| a\_k$, with $k > 1$, and integers $a\_i > 1$.

Given a tower of powers of height $3$, representing some integer $n$, how many towers of powers of
height *at least* $3$ represent $n$?

# Standard Input

The input file contains several test cases, each on a separate line. Each test case has the form
$a\verb|^|b\verb|^|c$, where $a$, $b$ and $c$ are integers, $ 1 < a, b, c \leq 9585$.

# Standard Output

For each test case, print the number of ways the number $n = a\verb|^|b\verb|^|c$ can be represented as a tower of powers of height at least three.

The magic number $9585$ is carefully chosen such that the output is always less than $2^{63}$.

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
<tr><td>4^2^2
8^12^2
8192^8192^8192
2^900^576</td><td>2
10
1258112
342025379</td></tr></table>


# Constraints



# Note



# Source


