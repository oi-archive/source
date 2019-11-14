
# Content

Marble (also called "Hitting the bricks") is a famous video game with a long history. During the game, the player is required to control a single ball to hit the bricks above. The ball will rebound when touching the wall or the paddle the player controls at the bottom. If the player's paddle misses the ball's rebound, the game will over.

Lvba developed a new version of the game. The new game is played inside a $S\times S$ square. There are no bricks, but a lot of balls. Those balls will move simultaneously at the beginning of the game. All the balls' horizontal and vertical velocity is equal to $1$ or $-1$, so there are four different moving directions in total. The player has a paddle at the bottom, if the paddle misses a ball's rebound, that ball will fall off and disappear. 

The goal of the new game is to find an initial position of the paddle at the bottom, and a strategy to move the paddle horizontally, to make sure that maximum number of balls will not fall off the bottom and will move inside the square forever. The moving speed of the paddle is also equal to $1$.

![title](/source/lutece/interesting-marble/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTc1LzIwMTQwODI3MjEyNzM2NDExMjIucG5n.png)

You may assume the balls are small enough to be regarded as points, and the paddle is a segment of length $1$. The ball will rebound when touching the paddle or the walls. The balls' initial positions are strictly inside the square. You should notice that the balls will not affect each other when their positions coincide.

Now given the initial position of the balls, and their moving directions, please find the maximum number of the balls that will be kept moving forever.

# Standard Input

The first line of the input will be an integer $T$ indicating the number of cases. ($T\leq 50$)

For each case, the first line contains two integers: $N$ ($1\leq N\leq 100$), $S$ ($1\leq S\leq 10000$), representing the number of the balls, and the side length of the square. Then $N$ lines follow, each in the format of `x y vx vy`.

$(x,y)$ is the position of the balls. We set the original point at the lower left corner of the square, the bottom as $x$-axis, and the left wall as $y$-axis.

$(v\_x,v\_y)$ is the ball's velocity at the beginning of the game, in which $v\_x$ and $v\_y$ equals $-1$ or $1$.

# Standard Output

For each case, you need to output two lines. Print `Case #k: S` first in a single line, in which $k$ represents the case number which starts from $1$, $S$ is the maximum number of balls the player can keep.

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
3 4
1 1 1 1
2 1 1 1
3 3 -1 1
2 4
1 1 -1 -1
2 1 -1 -1</td><td>Case #1: 3
Case #2: 2</td></tr></table>


# Constraints



# Note

1. It is not allowed to move the paddle out of the square.
2. The ball rebounds according to the physical law, for example, if a ball touches the left side of the wall with speed $(v\_x=-1, v\_y=1)$, its speed will turn to $(1,1)$; Moreover, if a ball touches the lower left corner with speed $(v\_x=-1, v\_y=-1)$, its speed will turn to $(1,1)$.
3. The picture shows the second case in sample input.

# Source


