
# Content

A regular dice is a cube with $6$ numbers ($1$ to $6$) on its $6$ faces. When you look at a corner of a dice you can see $3$ faces and of course the numbers on them. Now you're given $8$ views from $8$ corners of a dice, and your task is to tell what number is on the opposite side of a given number.

# Standard Input

One integer $T$ on the first line indicates the number of cases. 

Then followed by $T$ cases, every case contains $8$ lines. Each line contains $3$ integers $A$, $B$, $C$ describing the view from one corner of the dice (look at the picture for details). 

![.*](/images/problem/121/201402011233525444.png)

It's not guaranteed that the order of the $8$ views is given in the same way as the sample input.

# Standard Output

For each case, print $6$ integers separated by space on a line. The $i\_{th}$ number indicates the number on the opposite side of $i$.

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
1 2 3
1 3 4
1 4 5
1 5 2
6 3 2
6 4 3
6 5 4
6 2 5</td><td>6 4 5 2 3 1</td></tr></table>


# Constraints



# Note



# Source


