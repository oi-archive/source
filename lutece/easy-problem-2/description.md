
# Content

Given $n$ strings $A_i$, Each string has a `non-negative` cost $C_i$.

Let’s define the function of string $s$: $f(s) = \sum_{i=1}^n C_i * tot(s,i)$

$tot(s,i)$ represents the number of occurrences of $s$ in $A_i$ 

Find the maximal value of function $f(s)$ over all strings.

Note that $s$ is not necessary to be some string from $A$, and its length must be greater than zero.

# Standard Input

The first line is $n$ $(n \le 10^5)$, denoting the number of strings，containing only `a` to `z`.

Then $n$ lines each line is a string $A_i$.

Then a line contains $n$ integers $C_i$.

The sum of length of all the string will no more than $10^5$

$C_i \le 10000$

# Standard Output

Output one line representing the maximal value.

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
abc
abcd
cdab
1 2 3
</td><td>6</td></tr></table>


# Constraints



# Note

Let $S$ be `ab`, then the value will be $6$, it’s the maximal value.

# Source


