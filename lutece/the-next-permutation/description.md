
# Content

For this problem, you will write a program that takes a (possibly long) string of decimal digits, and outputs the permutation of those decimal digits that has the next larger value (as a decimal number)

than the input number. For example:
* `123` $\rightarrow$ `132`
* `279134399742` $\rightarrow$ `279134423799`

It is possible that no permutation of the input digits has a larger value. For example, `987`.

# Standard Input

The first line of input contains a single integer $P$, ($1\leq P\leq 1000$), which is the number of data sets that follow. Each data set is a single line that contains the data set number, followed by a space, followed by up to $80$ decimal digits which is the input value.

# Standard Output

For each data set there is one line of output. If there is no larger permutation of the input digits, the output should be the data set number followed by a single space, followed by the string **BIGGEST**. If there is a solution, the output should be the data set number, a single space and the next larger
permutation of the input digits.

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
1 123
2 279134399742
3 987</td><td>1 132
2 279134423799
3 BIGGEST</td></tr></table>


# Constraints



# Note



# Source


