
# Content

Captain Chen lives in two dimensional plane, so the stone he believes is a convex polygon.

Captain Chen loves stones, and he has a special rule to judge how beautiful a stone is. 

The rule is quite simple, the longer the visible part of the perimeter is, the more beautiful the stone is.

Now Captain Chen wonders what is the length of the visible part of the perimeter of the stone.

# Standard Input

The first line of the input contains one integer $N$ ($3\leq N\leq 10^4$), meaning the number of point in the polygon.

Each of the next N lines contains two real numbers $x\_{i}, y\_{i}$ ($-10^4\leq x, y\leq 10^4$), meaning the coordinate of the point.
The points of the polygon are given in anticlockwise.

The last line contains two real numbers $x, y$ ($-10^4\leq x, y\leq 10^4$), meaning the position of Captain Chen.

# Standard Output

Output the length Captain Chen can see, rounded to $0.001$

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
-1.0 0.0
1.0 0.0
1.0 1.0
-1.0 1.0
0 2</td><td>2.000</td></tr></table>


# Constraints



# Note

It is guaranteed that Captain Chen will not stand in the stone.

The image for the sample input, the perimeter Captain Chen can see is the line $AB$.

![title](/source/lutece/eh-beautiful-stone/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzk3LzIwMTQwMzI5MDEyNzI3MzE5Mi5wbmc=.png)

# Source


