
# Content

![.*](/source/lutece/curling/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE3LzIwMTQwMjAxMTIxNjEyOTY0MS5wbmc=.png)

Curling is one of StephYDX's favorite sports in the Vancouver 2010 Winter Olympics. StephYDX likes predicting how two curling stones moves after collision, but due to his poor knowledge of physics he always makes mistake. Now it's your turn to help him.

For simplicity, we regard the curling stone as a circle with unit radius on a $2$-D plane, and you can simply just ignore restriction of the curling sheet. In addition, all curling stones are of the same mass and collision between them is perfectly elastic (no energy loss). You will be given the initial $t = 0$ positions and velocities of two curling stones.

# Standard Input

One integer $T$ on the first line indicates the number of cases. Then followed by $T$ cases, every case contains $3$ lines.

The first line consists of $4$ float numbers $x, y, v\_x, v\_y$ which describe the initial position of the center $(x, y)$ and the initial velocity $(v\_x, v\_y)$ of one curling stone. The second line describes the other curling stone with the same format as the first line. The last line contains only one float number $t$.

It is guaranteed that two curling stones won't collide or intersect initially.

# Standard Output

For each case, print one line with $4$ float numbers $x\_1, y\_1, x\_2, y\_2$ separated by space, rounded to $3$ digits after the decimal point. $(x\_1, y\_1)$, $(x\_2, y\_2)$ are positions of the centers of the two curling stones after time $t$.

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
0 0 1 0
5 0 0 0
2.5
0 0 1 0
5 0 0 0
3.5</td><td>2.500 0.000 5.000 0.000
3.000 0.000 5.500 0.000</td></tr></table>


# Constraints



# Note



# Source


