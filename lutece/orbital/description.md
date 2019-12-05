
# Content

A game called Orbital in the android market became very hot now. In this game, there is a rectangle box with four vertexs placed on $A(0,0)$, $B(5,0)$, $C(5,10)$, $D(0,10)$. A launcher is located on the middle of the bottom edge $AB$ with coordinate $L(2.5, 0)$.

In each round, the launcher shoots one bullet along the direction decided by the player. One bullet flies $D$ unit length and then stop (if it never hit the bottom edge) to expand into a ball untill it touch the closest ball or a rectangle edge. If the bullet hit the edge(expect the bottom one) or a ball, it will reflat according to the law of reflection. If a flying bullet hit the bottom edge, the player will lose this game.

We just consider the most sample thing in this game. Given the shooting direction of the first bullet, can you find out the ball which it expands into?

# Standard Input

The first line contains one integer $T$, the number of test cases.

In each test case, the first line contains one integer $D$ and the second line contains two integers $(x,y)$ ($y>0$), a ray which starts from $(2.5, 0)$ and goes through point $(x, y)$ indicates the shoot direction of the bullet.

# Standard Output

For each case, output three read number(round to three decimal places) $x,y,r$, where $(x,y)$ is the center of the ball and $r$ is the radius. If the player loses, just output $-1$.

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
15
2.5 1</td><td>2.500 5.000 2.500</td></tr></table>


# Constraints



# Note



# Source


