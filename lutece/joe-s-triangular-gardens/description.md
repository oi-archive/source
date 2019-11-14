
# Content

Joe's landscaping company specializes in gardens for computer geeks who have just had their company go public. One of his signature features is a round pool surrounded by a tiled patio in the form of an equilateral triangle where the edge of the pool is tangent to each side of the triangle at its midpoint. 

![title](/source/lutece/joe-s-triangular-gardens/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzUwLzIwMTQwNDEwMjE1NzE4OTgzMjQucG5n.png)

Unfortunately, some of Joe's customers are not satisfied with an equilateral triangle, usually in the center of the garden. Some want it in a corner or next to a slope or some other layout. Joe would like the option of offering arbitrary triangular patios with an elliptical pool which is tangent to each side at the center of the side. For example: 

![title](/source/lutece/joe-s-triangular-gardens/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzUwLzIwMTQwNDEwMjE1NzIyODEyMjUucG5n.png)

Joe knows how to draw an ellipse by putting two stakes in the ground (at the foci of the ellipse), tying a rope between them and dragging a marker stick inside the rope. What Joe would like is for the customer to determine where the corners of the triangle will be and then measure the location of the triangle vertices and compute where to put the stakes and how long to make the rope.

Write a program, which takes as input the three vertices $(x\_1, y\_1)$ , $(x\_2, y\_2)$ and $(x\_3, y\_3)$ of a triangle and computes an ellipse inscribed in the triangle, which is tangent to each side of the triangle at its midpoint. The output is the coordinates of the two foci of the ellipse and the length of the rope (which is the sum of the distances from the foci to any point on the ellipse.

# Standard Input

The first line of input contains a single integer $N$ , ($1\leq N\leq 1000$) which is the number of data sets that follow. Each data set consists of a single line of input containing $6$ space separated floating point numbers $x\_1, y\_1, x\_2, y\_2, x\_3, y\_3$ giving the coordinates of the vertices of a triangle.

# Standard Output

For each data set, you should generate one line of output with the following values: The data set number as a decimal integer (start counting at one), a space and five floating point values accurate to two decimal places each separated by a single space. The values are $f\_{x\_1}, f\_{y\_1}, f\_{x\_2}, f\_{y\_2}, r\_l$ where ($f\_{x\_1}, f\_{y\_1}$) is one focus of the ellipse, ($f\_{x\_2}, f\_{y\_2}$) is the other focus of the ellipse and $r\_l$ is the sum of the distances from the foci to any point on the ellipse (e.g. the length of the rope). The foci should be listed in increasing lexicographical order (i.e. $f\_{x\_1}\leq f\_{x\_2}$ and if $f\_{x\_1} = f\_{x\_2}, f\_{y\_1}\leq f\_{y\_2}$ ). Note that in the case the ellipse is a circle, the two foci are the same (e.g. the center of the circle).

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
100 100 200 273.2051 300 100
100 100 100 300 300 100 
100 200 100 300 300 100</td><td>1 200.00 157.71 200.00 157.76 115.47 
2 119.53 213.81 213.81 119.53 163.30 
3 103.94 253.14 229.40 146.86 170.51</td></tr></table>


# Constraints



# Note



# Source


