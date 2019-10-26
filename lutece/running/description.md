
# Content

$A$ and $B$ are two students in BUPT. They usually go running together. The running route of $A$ is always along the runway, just like the one we usually see, is made up by two semicircles and two segments. As shown in the picture.

![title](/source/lutece/running/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjEzLzIwMTQwODI4MTMyOTE3Mzg5MjYuanBn.jpg)

The segments may degenerate, in other words, the runway maybe a circle. Unfortunately, there’s a monitor near them. Both monitor and people can be regarded as point on two-dimensional surface. The monitor can watch a person if and only if there’s no other one on the segment connecting the monitor and the person. Because $B$ don’t wish the monitor to watch $A$, he makes adjustments to his route continuously so that he is always on the segment connecting the monitor and $A$. For the sake of safety, the distance between the monitor and $B$ must be Dis at any time. Now you should write a program to calculate how long does $B$ run during the lap time of $A$.

Please notice that $A$ and $B$ are going running instead of any other things, so the positions of them can’t be same at any time.

# Standard Input

The first line of input data is a positive integer $T$ ($1 \leq T \leq 10000$), indicating the amount of test cases.

Then $T$ cases followed. For each case, the first line is three pairs of integers, the coordinates of centers of the two semicircle of runway of $A$, and the
coordinate of the monitor.

The second line is two positive integer $R$ and $Dis$, the radius of the semicircle and the distance between $B$ and the monitor.

The absolute values of all integers are not more than $10000$.

# Standard Output

For each test case, print one line.

If $B$ cannot prevent the monitor from watching $A$, print ”It is life.”(without quotes).

Otherwise, print the length of $B$’s running, round to two decimal places.

For more details, see the sample.

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
0 0 0 0 0 1
1 1
0 0 0 0 2 2
1 1</td><td>It is life.
1.45</td></tr></table>


# Constraints



# Note



# Source


