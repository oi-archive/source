
# Content

Maybe you have heard of Super Cow AC who is the great general of ACM Empire. However, do you know where he is from?

This is one of the ten biggest secrets of this world! And it is time to expose the truth! 

Yes, Super Cow AC is from ACStar which is ten million light-year away from our earth. No one, even AC himself, knows how AC came to our home. The only memory in his head is the strange rain in ACStar.

Because of the special gravity of ACStar, the raindrops in ACStar have many funny features. They have arbitrary sizes, color and tastes. The most interesting parts of the raindrops are their shapes. When AC was very young, he found that all the drops he saw in air were convex hull. Once the raindrops fell to the ground, they would be absorb by the soil.

![.*](/source/lutece/rain-in-acstar/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTk4LzIwMTQwMjAzMTcxNjQ0NDczMzgucG5n.png)

This year is set to be AC-year. In recognition of Great General AC's contribution to our empire, the Emperor decided to build a huge AC park. Inside this park there is a laboratory to simulate the rain in ACStar. As a researcher of this lab, you are appointed to measure the volume of rain absorbed by soil. To simplify this problem, scientists put the rain into two-dimensional plane in which the ground is represented as a straight line and the raindrops are convex polygon. So the area of the graphics stands for the volume of raindrops. 

You will receive two types of instructions:
1. `R P` (This type of instructions tell you sufficient information about the raindrops.)
2. `Q A B` (Ask you to report the volume of rain absorbed by soil of $[A,B]$.)

Instructions are given in chronological order.

# Standard Input

The first line of the inputs is $T$(no more than $10$), which stands for the number of test cases you need to solve. 

After $T$, the inputs will be each test case. The first line of each case will be $N$(no more than $25000$), representing for the numbers of instructions. The following $N$ lines will give instructions of the two types.

For each instruction of type $1$, it will be followed by a line listing $P$ (at least $3$ and at most $5$) points representing the convex polygon of the coming raindrop. The points are started by the leftmost point and are given in counterclockwise order. It's guaranteed that no points of the same raindrop are in the same vertical line. 

All numbers are positive integer no more than $1000000000$.

# Standard Output

For each instruction of type $2$, output the corresponding result, which should be printed accurately rounded to three decimals.

It is guaranteed that the result is less than $10^{8}$.

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
7
Q 1 100
R 4
10 10 11 10 13 11 12 11
Q 10 11
Q 1 100
R 3
100 20 120 20 110 30
Q 1 100
Q 12 120</td><td>0.000
0.250
1.000
1.000
100.250</td></tr></table>


# Constraints



# Note



# Source


