
# Content

$N$ numbers are given in a line, we want you to divide them into no more than $M$ piles so that the maximum number of the sum of each pile is minimal. You can't change the number's order.

# Standard Input

The first line contains a number $T$, denote the number of test cases.

For each test case,

In the first line, you will get $2$ numbers $N$ and $M$ ($1\leq M\leq N\leq 1000$) as described above.

In the next line, you will get the $N$ integers, all the integers are in the range of $[-100,100]$.

# Standard Output

For each test case, you should output a number in a line denote the minimal maximum sum.

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
9 3
1 9 2 4 7 3 0 6 5
3 2
1 3 -2</td><td>14
1</td></tr></table>


# Constraints



# Note

In the first case, you can divide the numbers as `1 9 2 / 4 7 3 0 / 6 5`

In the second case, you can divide the numbers as `1 / 3 -2`

# Source


