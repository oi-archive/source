
# Content

The big fight between England and Germany was destroyed by the guy called Larrionda. England could have made a tie of `2:2`. But that poor guy disqualified Lampard's wonderful goal. The ball passed through the goal line by half a meter, however, Larrionda turned a blind eye to this goal.

As a fan of Three Lion Regimen, silentsky want to develop a system which uses sensors to get the information to check if it scored or not.

The information includes a point as the location of ball, a vector as the velocity and a cuboid as the goal.

![title](/source/lutece/england-vs-germany/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjkxLzIwMTQwNDA5MjA0NDI4MTg3My5wbmc=.png)

# Standard Input

The first line gives an integer $t$ ($t\leq 10000$) indicating the number of test cases.

For each case:
1. The first line gives three real numbers $x, y , z$, indicating a point to represent the ball.
2. The second line gives three real numbers $a, b, c$. indicates a vector to represent the velocity.
3. The following $8$ lines give $8$ points according the sequence `A`, `B`, `C`, `D`, `E`, `F`, `G`, `H` as is shown in the figure.

Absolute value of all real numbers are smaller than $10000$.

It is guaranteed that the initial location of the ball is not inside the goal.

# Standard Output

if it scored then output `Case X: Stupid Larrionda!!!`.otherwise output `Case X: Intelligent Larrionda!!!`.($X$ is the case number starting from $1$).

(We consider `ABCD` as the front of the goal and `AB`, `BC`, `CD`, `DA` as the goalposts. A shoot scores if and only if it passes through the front of the goal and doesn't crash on the goalpost)

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
<tr><td>1
20 0 5 
-10 5 0 
10 0 10
10 10 10 
10 10 0
10 0 0 
0 0 10 
0 10 10 
0 10 0
0 0 0</td><td>Case 1: Stupid Larrionda!!!</td></tr></table>


# Constraints



# Note



# Source


