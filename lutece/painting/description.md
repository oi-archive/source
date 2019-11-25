
# Content

One day, pfctgeorge was very bored. He looked around his room, and noticed that there were a lot of $1\times 1\times 1$ cubic meter($m^3$) plastic white cubes. Then, he decided to stack these cubes into a $3$-Dimension object.

 We assume that pfctgeorge's room is a $3$-Dimensional space. Pfctgeorge stacked every cube located in $(x\_0,y\_0)$, that is, the cube was above of those cubes whose coordinate of $X$ is $x\_0$ and coordinate of $Y$ is $y\_0$ before stacking this cube, and its edge is perpendicular to $X$-axis,$Y$-axis of $Z$-axis respectively.

After stacking all the cubes into the object. Pfctgeorge noticed that there was a pail of colorful paint. So he wanted to painted the object into colorful. However, of course, he can only paint the surface of the object. 

Help pfctgeorge to figure out the colorful area of the object in square meter($m^2$) after his painting.

# Standard Input

The first line of the input contains an integer $T$($1\leq T\leq 20$) which means the number of test cases.

Then $T$ test cases follow, for every test case, the first line contains two integer $m$,$n$($1\leq m,n\leq 10$), means the pfctgeorge's room is $m$ meters in width and $n$ meters in length. Then $m$ lines follow, every line contains $n$ integers in the range of $0\cdots 100$. If $j\_{th}$ number of $i\_{th}$ line is $k$, it means there are $k$ cubes located in $(i,j)$.

# Standard Output

For each test case, you should output one line. First, output `Case #C: `, $C$ means the number of the test case which is from $1$ to $T$. Then, output an integer indicates the colorful area of the object in square meter after pfctgeorge's painting.

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
1
1 2
1 1
2 2
1 2
1 1</td><td>Case #1: 5
Case #2: 8
Case #3: 16</td></tr></table>


# Constraints



# Note

The picture below described the status of pfctgeoge's room after painting in the third sample.(The color of paint is blue.)

![title](/source/lutece/painting/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzA5LzIwMTQwNDA5MjIyMTM0ODgwMTIuanBn.jpg)

# Source


