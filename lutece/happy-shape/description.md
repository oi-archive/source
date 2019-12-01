
# Content

There is a circle and rectangle on the plane. The center of the circle is ($cx$, $cy$), and its radius is $cr$.

The edges of the rectangle parallel to the x-axis or the y-axis, and its bottom left corner is ($x1$, $y1$) and top right corner is ($x2$, $y2$). What is the area of their intersection?

# Standard Input

The first line of input contains a number, indicating the number of test cases. ($T \leq 10000$)

For each case, there will be seven integers $cx, cy, cr, x1, y1, x2, y2$, their meaning is described above. ($-1000 \leq cx, cy, cr, x1, y1, x2, y2 \leq 1000, x1 \lt x2, y1 \lt y2$)

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$).

Then output the area of the intersection of the circle and the rectangle, in decimals, round to $4$ decimal places.

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
0 0 2 -1 -1 1 1
0 0 1 0 0 2 2
1 1 1 100 100 200 200</td><td>Case #1: 4.0000
Case #2: 0.7854
Case #3: 0.0000</td></tr></table>


# Constraints



# Note



# Source


