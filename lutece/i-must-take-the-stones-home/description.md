
# Content

After finding the beautiful stone, our Captain Chen feels excited. He decides to take the stone home. Hear we regard the stone as a convex polygon.

Captain Chen will choose a corner of the stone, and choose a direction to pull the stone.

The stone has weight, and it will have friction with the ground. Here we assume the maximum `coefficient of static friction` equals the `coefficient of kinetic friction`, therefore you can simply assume $F\_{f} = \mu F\_{N}$.

Here is a simple graph showing the stone and the pulling force of Captain Chen.

![title](/source/lutece/i-must-take-the-stones-home/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODAxLzIwMTQwMzI4MjI0NzMzNjAzMS5wbmc=.png)

**In our problem, $F\_{y}$ will always points up.**

However, there might be other problems! The stone might spinning around some point on the ground, and begin to rolling. We have to consider this problem.

Here is an example of spinning

![title](/source/lutece/i-must-take-the-stones-home/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODAxLzIwMTQwMzI4MjI1OTE2MDgwMy5wbmc=.png)

Here, we have $F = 1.5N, G = 6N$, you can see that the stone will spinning around the point $A$, if you do not understand why, you have to understand the idea of `torque`.

Torque, moment or moment of force (see the terminology below), is the tendency of a force to rotate an object about an axis, fulcrum, or pivot. Just as a force is a push or a pull, a torque can be thought of as a twist to an object. Mathematically, torque is defined as the cross product of the lever-arm distance vector and the force vector, which tends to produce rotation.

In the picture above, $F$ will make the stone spinning counter-clockwise, while the gravity try to make the stone spinning clockwise. When the value of $F$ is too big, the stone will spinning around point $A$.

The torque $F$ given to point A is $1.5N\times 4m$, while the torque $G$ given to point A is $6N\times1m$

So, if Captain wants to take the stone home, he has to consider both `force balance` and `torque balance`.

Tell us the minimum force Captain Chen has to take, given the corner Captain Chen chooses and the direction Captain Chen will try to pull the stones to.

# Standard Input

The first line of input contains a single number $n$, which is the number of points on the stone. $(3\leq n\leq 50)$

Then come $n$ lines each with two numbers $x\_{i}$ and $y\_{i}$, the position of the points. $(-1000\leq x\_{i}, y\_{i}\leq 1000, y\_{0} = y\_{1}=0)$

We consider that the first point and the second point will always be on the ground, and the points are given in counter-clockwise direction.

Then comes a line with a number $id$, the id of the corner Captain Chen decides to pull the stone on. $(2\leq id\leq n - 1)$

Then comes a line with two numbers $dx$ and $dy$, the direction Captain Chen will pull the stone. $-1000\leq dx\leq 1000, 0\leq dy\leq 1000$

It is guaranteed that this direction will point to the outside of the stone.

The last line comes with two numbers $\mu$ and $m$, given the `coefficient of kinetic friction` of the stone and the weight of the stone.

We always assume $g = 9.8N/kg$, and the gravity $G = mg$.

# Standard Output

The miminum force to move the stone, rounded to $0.001$.

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
<tr><td>11
181.00 0.00
506.14 0.00
557.10 0.22
665.30 74.71
789.08 200.92
665.47 455.89
179.19 363.04
-56.56 307.79
-196.92 170.66
-214.00 84.04
-143.54 53.85
10
-328.13 23.53
0.85 98.77</td><td>777.477</td></tr></table>


# Constraints



# Note

You can use `printf("%.3f\n")` to output the result.

# Source


