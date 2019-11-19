
# Content

In a $1964$ paper on continuous mappings of the reals into the reals, $Alexandr$ $Sharkovski$ used the following ordering of the positive integers:

$3$ ◄ $5$ ◄ $7$ ◄ $9$ ◄ $...$ ◄ $3·2$ ◄ $5·2$ ◄ $7·2$ ◄ $...$ ◄ $3·2^2$ ◄ $5·2^2$ ◄ $...$ ◄ $2^3$ ◄ $2^2$ ◄ $2$ ◄ $1$

As $Ciesielski$ and $Pogoda$ $(2008)$ describe it:

“First come the odd numbers, beginning with $3$, arranged in increasing order. This sequence is repeated with each odd integer multiplied by $2$. The initial sequence is again repeated with each odd integer multiplied by $2^2$, and so on. The terminal sequence consists of the nonnegative powers of $2$ arranged in decreasing order (note that $1 = 2^0$).”

Write a program that reads an input containing a list of up to $255$ unsigned integers with values less than or equal to $65,535$ (not necessarily distinct) separated by white space and terminated by ‘$0$’. The program should display on the screen the numbers arranged in Sharkovski’s ordering in one line. The numbers in the line are separated exactly by one space.

# Standard Input

The input starts with an integer $N$ $(0 ≤ N ≤ 255)$. This is followed by $N$ input cases. Each input case is a non-empty list of up to $255$ unsigned integers (not necessarily distinct) with values not exceeding $65,535$. Each pair of numbers is separated by white space. Each input case is terminated by ‘$0$’.

# Standard Output

For every input case, print the required numbers arranged in Sharkovski’s ordering in one line. The numbers in the line are separated exactly by one space.

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
3 0
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 1 0</td><td>3
3 5 7 9 11 13 15 17 19 6 10 14 18 12 16 8 4 2 1 1</td></tr></table>


# Constraints



# Note



# Source


