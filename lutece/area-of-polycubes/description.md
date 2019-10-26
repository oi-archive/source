
# Content

A polycube is a solid made by gluing together unit cubes (one unit on each edge) on one or more faces. The figure in the lower-left is not a polycube because some cubes are attached along an edge. 

![title](/source/lutece/area-of-polycubes/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzQ4LzIwMTQwNDEwMjE0NTU4MDQ5MjIucG5n.png)

For this problem, the polycube will be formed from unit cubes centered at integer lattice points in $3$-space. The polycube will be built up one cube at a time, starting with a cube centered at $(0,0,0)$. At each step of the process (after the first cube), the next cube must have a face in common with a cube previously included and not be the same as a block previously included. For example, a $1$-by-$1$-by-$5$ block (as shown above in the upper-left polycube) could be built up as:

$$(0,0,0)\rightarrow (0,0,1)\rightarrow (0,0,2)\rightarrow (0,0,3)\rightarrow (0,0,4)$$

and a $2$-by-$2$-by-$2$ cube (upper-right figure) could be built as:

$$(0,0,0)\rightarrow (0,0,1)\rightarrow (0,1,1)\rightarrow (0,1, 0)\rightarrow  (1,0,0) \rightarrow (1,0,1) \rightarrow (1,1,1)\rightarrow  (1,1, 0)$$

Since the surface of the polycube is made up of unit squares, its area is an integer.

Write a program which takes as input a sequence of integer lattice points in 3-space and determines whether is correctly forms a polycube and, if so, what the surface area of the polycube is.

# Standard Input

The first line of input contains a single integer $N$ , ($1\leq N\leq 1000$) which is the number of data sets that follow. Each data set consists of multiple lines of input. The first line contains the number of points $P$ , ($1 = P = 100$) in the problem instance. Each succeeding line contains the centers of the cubes, eight to a line (except possibly for the last line). Each center is given as $3$ integers, separated by commas. The points are separated by a single space.

# Standard Output

For each data set, you should generate one line of output with the following values: The data set number as a decimal integer (start counting at one), a space and the surface area of the polycube if it is correctly formed, OR, if it is not correctly formed, the string `NO` a space and the index (starting with $1$) of the first cube which does not share a face with a previous cube. Note that the surface area includes the area of any included holes.

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
<tr><td>4 
5 
0,0,0 0,0,1 0,0,2 0,0,3 0,0,4 
8 
0,0,0 0,0,1 0,1,0 0,1,1 1,0,0 1,0,1 1,1,0 1,1,1 
4 
0,0,0 0,0,1 1,1,0 1,1,1 
20 
0,0,0 0,0,1 0,0,2 0,1,2 0,2,2 0,2,1 0,2,0 0,1,0 
1,0,0 2,0,0 1,0,2 2,0,2 1,2,2 2,2,2 1,2,0 2,2,0 
2,1,0 2,1,2 2,0,1 2,2,1</td><td>1 22 
2 24 
3 NO 3 
4 72</td></tr></table>


# Constraints



# Note



# Source


