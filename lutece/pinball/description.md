
# Content

Maria is quite addicted to pinball. She can shoot the ball to any position at the top of the board, but she cannot predict where the ball will end when it falls down, because it hits many bumpers on its way down.

She decided to model the pinball table as line segments and assume that the ball is a point that falls from infinite height. The ball falls straight vertically unless there is a segment immediately below it, in which case it follows the direction of the segment downwards until its end.

As you would expect the segments are closed, that is an endpoint is part of its segment. Pairs of segments do not intersect, not even at endpoints, and none is vertical or horizontal. Segments are not given in any specific order.

# Standard Input

The first line contains an integer $N$ $(0\leq N\leq 100 000)$, the number of segments. Then $N$ lines follow, each with four integers $x\_1, y\_1, x\_2, y\_2$, the coordinates of a segment $(-1 000 000\leq x\_i,y\_i\leq 1 000 000)$. The last line contains an integer $x\_0$ $(-1 000 000\leq x\_0\leq 1 000 000)$, the initial x-coordinate of the ball.

# Standard Output

Output a single integer $x\_T$ , the final x-coordinate of the ball.

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
-1 1 1 -1
1 -2 2 -3
0</td><td>2</td></tr><tr><td>3
-1 1 1 -1
1 -2 0 -3
1 -3 2 -4
0</td><td>0</td></tr></table>


# Constraints



# Note

![title](/source/lutece/pinball/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODYzLzIwMTQwNTA0MDI1NjUyODE5MTcucG5n.png)

# Source


