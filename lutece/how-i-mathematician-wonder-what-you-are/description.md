
# Content

After counting so many stars in the sky in his childhood, Isaac, now an astronomer and a mathematician uses a big astronomical telescope and lets his image processing program count stars. The hardest part of the program is to judge if shining object in the sky is really a star. As a mathematician, the only way he knows is to apply a mathematical definition of stars.

The mathematical definition of a star shape is as follows: A planar shape F is star-shaped if and only if there is a point $C ∈ F$ such that, for any point $P ∈ F$, the line segment $CP$ is contained in $F$. Such a point $C$ is called a center of $F$. To get accustomed to the definition let’s see some examples below.

![title](/source/lutece/how-i-mathematician-wonder-what-you-are/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjgxLzIwMTQwMzE5MDAzNzI5NzczNy5wbmc=.png)

The first two are what you would normally call stars. According to the above definition, however, all shapes in the first row are star-shaped. The two in the second row are not. For each star shape, a center is indicated with a dot. Note that a star shape in general has infinitely many centers. Fore Example, for the third quadrangular shape, all points in it are centers.

Your job is to write a program that tells whether a given polygonal shape is star-shaped or not.

# Standard Input

The input is a sequence of datasets followed by a line containing a single zero. Each dataset specifies a polygon, and is formatted as follows.

$n$
	
$x\_1$	$y\_1$

$x\_2$	$y\_2$

$ \cdots $

$x\_n$	$y\_n$

The first line is the number of vertices, $n$, which satisfies $4 \leq n \leq 50$. Subsequent $n$ lines are the $x-$ and $y-$coordinates of the $n$ vertices. They are integers and satisfy $0 \leq x\_i \leq 10000$ and $0 \leq y\_i \leq 10000 (i = 1, \cdots, n)$. Line segments $(x\_i, y\_i)–(x\_i + 1, y\_i + 1) (i = 1, \cdots, n - 1)$ and the line segment $(x\_n, y\_n)–(x\_1, y\_1)$ form the border of the polygon in the counterclockwise order. That is, these line segments see the inside of the polygon in the left of their directions.

You may assume that the polygon is simple, that is, its border never crosses or touches itself. You may assume assume that no three edges of the polygon meet at a single point even when they are infinitely extended.

# Standard Output

For each dataset, output `1` if the polygon is star-shaped and `0` otherwise. Each number must be in a separate line and the line should not contain any other characters.

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
66 13 
96 61 
76 98 
13 94 
4 0 
45 68 
8 
27 21 
55 14 
93 12 
56 95 
15 48 
38 46 
51 65 
64 31 
0</td><td>1
0</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by 695375900. So any mistake here does not imply mistake in the offcial judge data.

# Source


