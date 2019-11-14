
# Content

A `lattice point` is a point with integer coordinates. A `lattice polygon` is a polygon with all vertices lattice points.

![title](/source/lutece/interior-points-of-lattice-polygons/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzU4LzIwMTQwNDEwMjIyMjI0NDcyMjcuanBn.jpg)

The lattice points on the boundary of the polygon are boundary points (open dots in the figure above) and the points inside and not on the polygon are interior points (filled in dots in the figure above).

A polygon is convex if any line segment between two points of the polygon is inside (or on the boundary of) the polygon. Equivalently, the interior angle at each polygon vertex is less than $180$ degrees. Note that any line between two points inside (and not on the boundary of) the polygon is entirely inside (and not on the boundary of) the polygon.

The interior points of a convex lattice polygon on any horizontal line form a single segment from a leftmost point to a rightmost point (which may be the same). Note that there may be no interior points ($A$), or only one ($B$), or isolated points ($C$) as shown in the figures below.

![title](/source/lutece/interior-points-of-lattice-polygons/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzU4LzIwMTQwNDEwMjIyMjQ3MTEyMjguanBn.jpg)

Write a program that reads the vertices of a convex lattice polygon in standard order and outputs the interior points as a list of horizontal line segments. The vertices of a lattice polygon are in standard order if:

1. The first vertex is the one with the largest y value. If two vertices have the same $y$ value, the one with the smaller $x$ value is the first.
2. Vertices are given in clockwise order around the polygon.

# Standard Input

The first line of input contains a single integer $P$, ($1\leq P\leq 1000$), which is the number of data sets that follow. The first line of each data set contains the data set number, followed by a space, followed by a decimal integer giving the number vertices $N$, ($3\leq N\leq 50$), of the polygon. The remaining lines in the data set contain the vertices, one per line in standard order. Each line contains the decimal integer $x$ coordinate, a space and the decimal integer $y$ coordinate.

# Standard Output

For each data set there are multiple lines of output. The first line contains a decimal integer giving the data set number followed by a single space, followed by a decimal integer giving the number of horizontal lines which contain interior points (this may be zero ($0$) or more). The lines of interior points, if any, follow, one per line in order of decreasing y value. Each line contains the decimal integer $y$ coordinate, a single space and the decimal integer $x$ coordinate of the left most point, a single space and the decimal integer $x$ coordinate of the right most point.

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
<tr><td>6
1 8
5 10
8 9
11 6
10 2
6 0
1 1
0 4
2 8
2 4
3 10
13 7
10 -3
0 0
3 3
1 3
3 1
1 1
4 3
1 4
4 1
1 1
5 4
0 6
2 3
3 0
1 3
6 6
1 3
3 3
4 2
3 1
1 1
0 2</td><td>1 9
9 4 7
8 3 8
7 2 9
6 2 10
5 1 10
4 1 10
3 1 10
2 1 9
1 2 7
2 12
9 3 6
8 3 9
7 3 12
6 2 12
5 2 12
4 2 12
3 1 11
2 1 11
1 1 11
0 1 10
-1 4 10
-2 7 10
3 0
4 1
2 2 2
5 2
4 1 1
2 2 2
6 1
2 1 3</td></tr></table>


# Constraints



# Note



# Source


