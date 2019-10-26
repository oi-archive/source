
# Content

On a two dimension plane, you are given a convex polygon and a point which is out of the polygon. You should find a ray whose endpoint is the given point, and divides the convex polygon into two parts with equal area.

# Standard Input

First an integer $T$ indicates the number of test cases.

Every test case begins with an integer $N$, which is the number of vertexes of the convex polygon. Then $N$ points follow, specifying the convex polygon in counterclockwise. Finally a point which is the endpoint of the ray ends the test case. A point is consist of two integers $(x, y)$, and the area of the convex polygon is positive.

$T \leq 100$;

$3 \leq N \leq 100$;

$-10000 \leq x, y \leq 10000$;

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then output the unit direction vector of the ray rounding to four digits after the decimal point. See sample for more details.

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
3
1 0
1 1
0 1
0 0
3
1 -1
2 0
1 1
0 0</td><td>Case #1: 0.7071 0.7071
Case #2: 1.0000 0.0000</td></tr></table>


# Constraints



# Note



# Source


