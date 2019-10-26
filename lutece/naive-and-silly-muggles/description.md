
# Content

Three wizards are doing a experiment. To avoid from bothering, a special magic is set around them.
The magic forms a circle, which covers those three wizards, in other words, all of them are inside or on the border of the circle.
And due to save the magic power, circle's area should as smaller as it could be.

Naive and silly `muggles`(who have no talents in magic) should absolutely not get into the circle, 
nor even on its border, or they will be in danger.

Given the position of a muggle, is he safe, or in serious danger?

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

For each test case there are four lines.
Three lines come each with two integers $x\_i$ and $y\_i$ ($\left | x\_i, y\_i \right | \leq 10$), indicating the three wizards' positions.
Then a single line with two numbers $q\_x$ and $q\_y$ ($\left | q\_x, q\_y \right | \leq 10$), indicating the muggle's position.

# Standard Output

For test case $X$, output `Case #X: ` first, then output `Danger` or `Safe`.

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
0 0
2 0
1 2
1 -0.5

0 0
2 0
1 2
1 -0.6

0 0
3 0
1 1
1 -1.5</td><td>Case #1: Danger
Case #2: Safe
Case #3: Safe</td></tr></table>


# Constraints



# Note



# Source


