
# Content

A good number is defined as all digits in decimal system are between $1$ and $9$, inclusive. The value of one good number can be calculate as follow:

Insert `+` into some of the positions (possibly none) between two digits.

After insertion, this good number can be evaluated as formulas, and the result is $S$.

The value is sum of $S$ of all possible legal insertion. The legal insertion is that any two neighbor digits can insert no more than one `+`. Inserting before the first digit or after the last digit is illegal.

Alfa wants you to calculate the value.

# Standard Input

The first line is an integer $T$($1 \leq T \leq 52$), which indicates the number of testcases.

For each testcase:

The one line of the input file contains a good number $N$($1 \leq |N| \leq 10^5$).

$|N| \leq 10^5$ means the length of N no more than $10^5$ and $N$ is positive integer.

# Standard Output

For each testcase, your program should output the value of the good number mod $10^9 + 7$.

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
157</td><td>250</td></tr><tr><td>1
315</td><td>378</td></tr></table>


# Constraints



# Note

In the first example, the answer is calculated as follow:

157 = 157

1 + 57 = 58

15 + 7 = 22

1 + 5 + 7 = 13

157 + 58 + 22 + 13 = 250

# Source


