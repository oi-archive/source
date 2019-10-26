
# Content

A big hall is paved with square tiles of unit side length (which means it is $1 \times 1$ in size). Tragedy happened when a careless porter passed through the hall. The heavy box he carried happened to fall down on the floor,and some tiles are cracked. Undoubtedly some tiles must be replaced, but the question came that how many tiles were cracked in the accident.

For convenience, we build a norml Cartesian coordinate system, and we assume that the bottom of the box is a rectangle with all its vertices on the lattice point (that is to say both of its $x$ and $y$ coordinate are integers). A tile is cracked if and only if the the rectangle has a positive intersection with it.

# Standard Input

One integer $T$ on the first line indicates the number of cases.

Then followed by $T$ cases, one line for each case.

Each line with $4$ pairs of integers ($x_i, y_i$) describe $4$ vertices (in counter-clockwise order) of the rectangle mentioned above.
($0 \leq x_i, y_i \leq 10000$)

# Standard Output

For each case, print one line with the number of cracked tiles.

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
0 0 5 0 5 3 0 3
1 0 3 2 2 3 0 1</td><td>15
7</td></tr></table>


# Constraints



# Note



# Source


