
# Content

In order to compare race tracks, we wish to compute their lengths. A racetrack is strictly two-dimensional (no elevation). It is described by two simple polygons, where one is completely contained inside the other. The track is the region between these two polygons. We define the length of the track as the absolute minimum distance that one needs to travel in order to complete a lap. This could involve traveling on the very edge of the track and arbitrarily sharp cornering (see Figure 1).

![title](/source/lutece/around-the-track/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTExMi8yMDE1MDUxNTIzMTc0NTkzOTY2LmpwZw==.jpg)

Figure 1: Illustration of sample input number 3 together with the shortest route around the track (dashed).

# Standard Input

The input consists of:

>#####one line with one integer n $(3≤n≤50)$, the number of vertices of the inner polygon;
>#####n lines, the ith of which contains two integers xi and yi $(−5000≤xi,yi≤5000)$: the coordinates of the ith vertex of the inner polygon;
>#####one line with one integer m $(3≤m≤50)$, the number of vertices of the outer polygon;
>#####m lines, the ith of which contains two integers xi and yi $(−5000≤xi,yi≤5000)$: the coordinates of the ith vertex of the outer polygon.

For both polygons, the vertices are given in counterclockwise order. The borders of the two polygons do not intersect or touch each other.

# Standard Output

Output one line with one floating point number: the length of the race track. Your answer should have an absolute or relative error of at most $10^{−6}$.

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
1 1
2 1
1 2
3
0 0
4 0
0 4</td><td>3.41421356237309</td></tr><tr><td>5
1 1
5 1
5 5
3 3
1 5
4
0 0
6 0
6 6
0 6</td><td>16</td></tr><tr><td>5
1 1
5 1
5 5
3 3
1 5
5
0 0
6 0
6 6
3 4
0 6</td><td>16.4721359549996</td></tr></table>


# Constraints



# Note



# Source


