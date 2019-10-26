
# Content

Yesterday, a rocket from the neighbor country hit your country, and caused a big hole. The Field Force measured the length
of destroyed wall. As the most prestigious scientist, you are required by goverment to calculate the maximum lethal radius
that could cause the disaster of the measured length to estimate the military strength of the neighbor country.  The walls
in your country are built in the shape of circle or convex polygon.

# Standard Input

First line of the input is a single integer $T$($1 \leq T \leq 300$), indicating there are $T$ test cases.

The first line of each test case contains a integer $N$ ($1 \leq N \leq 300$) and real number $M$ ($1 \leq M \leq10^4$), which represents
number of walls and total destroyed length.

Each of the next $N$ lines represents a wall. 

$C\ X\ Y\ R$ means the wall is in the shape of circle with the center in $(X,Y)$ and a radius of $R$.

$P\ N\_p\ X\_1\ Y\_1\ X\_2\ Y\_2\ \\cdots$ means the wall is in the shape of convex polygon with $N\_p$ points and the coordinate of those
points(showed in clockwise order or anti-clockwise order) is $X\_1 Y\_1 \cdots X\_{N\_p} Y\_{N\_p}$.

The last line of the test case contains the coordinate of the landing site of the rocket.

# Standard Output

For each case, you should output a single line, first output `Case #t: `, where $t$ indicating the
case number between $1$ and $T$. Then a single real number follows, indicating the lethal radius of the rocket.

If it is impossible to cause a disaster with the given destroyed length, output `impossible` other than the real number.
Besides, if the lethal radius of the rocket can be any real number greater than a particular real number, output
`inestimable` instead of others.

Round the answer to the second digit after the decimal point.

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
1 1.0
C 2.0 0.0 1.0
0.0 0.0
1 4.0
P 4 0.0 0.0 1.0 0.0 1.0 1.0 0.0 1.0
4.0 4.0
1 5.0
P 4 0.0 0.0 1.0 0.0 1.0 1.0 0.0 1.0
4.0 4.0
</td><td>Case #1: 1.22
Case #2: inestimable
Case #3: impossible
</td></tr></table>


# Constraints



# Note

All the numbers used to represent coordinate are real numbers which absolute value are less than $10^4$.

The total points in the each test case are no more than $300$. The total points here consist of the center of
the circle and the points of polygon.

The pictures below are just for fun.

![.*](/source/lutece/invasion/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTEvMjAxNDAxMTMxODMxNTYwMDQyMi5wbmc=.png)

![.*](/source/lutece/invasion/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTEvMjAxNDAxMTMxODMyMDM2NjAyMy5wbmc=.png)

# Source


