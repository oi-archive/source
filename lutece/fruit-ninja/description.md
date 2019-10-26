
# Content

These days wolf5x is addicted to a game on the mobile phone called Fruit Ninja. In this game, some fruits will be thrown up into the air, while the player should swipe his finger as a blade across the screen to slash them. Sometimes bombs are thrown out too, and he must avoid them, for he doesn’t want to be blown to pieces. But wolf5x is really a poor player and often misses the target. He thinks this is because the blade is so difficult to use. So he changes his weapon to a rectangular BanZhuan. Now wolf5x wants to use this to smash as many fruits as possible while no bomb is touched. Also he wants to know how many ways there are to reach the goal. Can you help him to figure out the answer?

To make it clear, we regard the fruits and bombs as points on the plane. The BanZhuan is an $H\times W$ rectangle. We require that the $W$-edge of the BanZhuan be paralleled to the $X$-axis, and the $H$-edge be paralleled to the $Y$-axis. The fruits or the bombs on the edge of the BanZhuan are considered touched. Two ways are different if the BanZhuan doesn't smash exactly the same area.

# Standard Input

Multiple cases. On the first line is an integer $T$ indicating the case number.

In each case, first come three integers $N, H, W$ in a line separated by spaces. $N$ is the number of objects(fruits and bombs in total). $H$ and $W$ are the height and the width of the BanZhuan.

Then follow $N$ lines in the format $L, X, Y$, where $L$ is letter `G` or `B`, indicating this is a Good fruit or a Bomb. $X$ and $Y$ are integers. $(X,Y)$ is the coordinate of the object. No two objects are overlapped.

For all cases, $1\leq N\leq 50000$, $1\leq X,Y,H,W\leq 25000$.

# Standard Output

First line, if there are finite ways to get maximum number of fruits, output an integer, the number of ways. Otherwise output `so many!`.

Second line, and integer, the maximum number of fruits wolf5x can smash at one time.

Output a blank line after each case.

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
4 2 3
G 0 1
G 0 2
G 1 2
G 3 0
4 2 3
B 0 1
B 0 2
G 1 2
G 3 0
4 2 3
B 0 1
B 1 2
G 1 1
B 3 0</td><td>1
4

so many!
2

so many!
0</td></tr></table>


# Constraints



# Note

In the first sample, if we put the lower-left vertex of the BanZhuan at $(0,0)$ and the upper-right vertex at $(3,2)$, then we can smash all the four fruits. And this is the only way to get all of them.

# Source


