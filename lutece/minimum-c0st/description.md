
# Content

There are $N$ numbers where the $i^{th}$ is $A_i$.

In order to make the sum of them changed to $S$, you can make some numbers increased by one or decreased by one.

But you should spend $C_i$ dollars to increase or decreased $A_i$ by one, and the new $A_i$ should satisfies $L_i\leq A_i\leq R_i$.

Any number can be operated any times. What's the minimum cost to make the sum of all numbers changed to $S$?

# Standard Input

The first line contains two integers $N, S$,

Next $N$ lines each line contains four integers $A_i, C_i, L_i, R_i$.

$1\leq N\leq 1000, 1\leq S\leq 10^6, 1\leq C_i\leq 1000, 0\leq L_i\leq A_i\leq R_i\leq 1000$

# Standard Output

If there is no solutions, print `impossible`.

Otherwise, print one integer indicates the minimum cost to make the sum of all numbers changed to $S$.

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
<tr><td>3 6
1 1 1 3
1 2 1 3
1 3 1 3</td><td>4</td></tr></table>


# Constraints



# Note



# Source


