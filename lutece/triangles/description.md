
# Content

You got a very strange gift for your birthday: two triangles in the three-dimensional space. Each
triangle consists of three infinitely thin segments, and each segment stays straight no matter how
hard you press it. Now, you actually wanted to get just one triangle, so you try to move the triangles
far apart from each other, possibly after rotating one or both of them, so that you can throw away
one of them. Is it possible? Or are they tangled?

# Standard Input

The input consists of several lines. The first line contains $1\leq T\leq 1000$, the number of test cases.

Each test case consists of two lines. The first line contains $9$ integers $x_1 ,y_1 ,z_1 ,x_2 ,y_2 ,z_2 ,x_3 ,y_3 ,z_3\in 
[−1000,1000]$ denoting the vertices of the first triangle. 
The second line contains another $9$ integers $x'_1 ,y'_1 ,z'_1 ,x'_2 ,y'_2 ,z'_2 ,x'_3 ,y'_3 ,z'_3 \in [−1000,1000]$ denoting the vertices of the second triangle. 

Both triangles will be non-degenerate, which means that the corresponding triples of points will not be 
colinear. Moreover, it is guaranteed that no pair of segments from two different triangles intersects,
and there is no common plane containing both triangles at once.

# Standard Output

For each test case, output one line containing `YES` if the triangles are tangled, and `NO` if it is possible
to move them very far apart from each other.

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
0 0 0 10 0 0 0 10 0
1 1 10 1 1 -10 10 10 0
0 0 0 10 0 0 0 10 0
11 0 0 0 11 0 11 11 1</td><td>YES
NO</td></tr></table>


# Constraints



# Note



# Source


