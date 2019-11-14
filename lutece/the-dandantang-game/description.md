
# Content

Xiaoming is a boy who enjoys playing computer games, especially some leisure online games, for example, dandantang. His game account is `Aria`, the name of an animation which be particularly loved by Xiaoming. Xiaoming is very poor, so he doesn’t want to spend money on the game. Therefore, Xiaoming’s daily tasks must be completed in exchange for the game coin, it is boring. The only interesting thing is cooperating with Aleng, a girl in the same sociaty, to fight with the other players in the game. Chat with a girl while playing the boring game is a nice thing , it can make Xiaoming forget the disappointment when he fails in the battle.

Rules of Dandantang are very simple, each player takes action in turn, fires shells towards the enemy. Before firing, player must control two parameters: the direction and the power.

Direction. Each player can adjust the direction of firing, makes the shells to get an initial velocity in this specific direction. The directions are measured by angles, the unit is degree. The angle is base on the horizontal line, The angle above the horizon is positive while under the horizon is negative. According to the location and the type of weapon, the adjustable range of angle may vary.

Power. The velocity is decided by the power, we can assume that for every $1$ unit increase in power, we can get $1m/s$ increase in velocity. That is, if the firing power is $15$, we can get an initial velocity of $15m/s$.

![title](/source/lutece/the-dandantang-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjM3LzIwMTQwMzE4MTQ1NDE1NTc5MTMuZ2lm.gif)

After firing, the shells will be affected by gravity and the wind, but we ignore the effect of the wind and assume the acceleration due to gravity to be $10m/s^2$.Shells will explode when in collision with the obstacles. If the enemy positions in the explosion happened, then it will be hurt by the shells. On one occasion, Xiaoming and Aleng were performing a task. They entered the final battle after $4$ rounds. Unfortunately, The other two teammates got disconnected(because of the BUG of the game ), it made the simple task became very difficult. Soon Aleng was killed by the Big Boss, Xiaoming realized that he also unable to withstand any attack by the Big Boss. If he died, Aleng and he would lose the chance to get the reward, he didn’t hope such a thing happen. But nothing is impossible, because his rage was full, the shells was more lethal. As long as the shells can hit the Big Boss, Xiaoming would be able to get rid of it in one round.

After a long period of practice, Xiaming have mastered a unique skill: $60$-degree fixed angle fire. He can hit anywhere in a $60$-degree angle if possible, only need to adjust the power of shells. But this skill has three weaknesses: Obstacle, if the shells hit an obstacle before hit the target, shells will explode immediately.

The adjustable range of the cannon is very limited, can only adjust to an angle between $45$ degrees to $75$ degree with tangent line of current position. In other words, if the location is bad, the angle can’t able to adjust to $60$ degrees, the skill can’t be used.

No matter how much power of the shells, the enemy can’t be hit. For example, the enemy is located on right above Xiaoming.

That is if Xiaoming don’t encounter any of the three cases above, he can hit the target absolutely. Now please help Xiaoming to determine whether xiaoming could use his unique skills, to give the Big Boss the final blow.

# Standard Input

The first line of input is an integer $C$, which is the number of test case. Each test case is given in the following format.

$n$

$X\_{xiaoming}$ $Y\_{xiaoming}$ $X\_{boss}$ $Y\_{boss}$

$M\_1$

$x\_1$  $y\_1$

$x\_2$  $y\_2$

$……$

$x\_{M\_1}$  $y\_{M\_1}$

$M\_2$

$x\_1$  $y\_1$

$x\_2$  $y\_2$

$……$

$x\_{M\_2}$  $y\_{M\_2}$

$……$

$M\_n$

$x\_1$  $y\_1$

$x\_2$  $y\_2$

$……$

$x\_{M\_n}$  $y\_{M\_n}$

A positive integer $n$ is the number of the obstacles. $X\_{xiaoming}$ and $Y\_{xiaoming}$ are the values of $x$-coordinate and $y$-coordinate of the position of Xiaoming, Xboss and Yboss are the values of $x$-coordinate and $y$-coordinate of the position of the Big Boss. The following is the description of the obstacles, we use polygons to represent the obstacles. the first line of each polygon is an integer $m\_i$, the number of vertices which make the polygon, the vertices of the polygon are arranged in a counter-clockwise order. You may assume that the polygon is simple, that is, its border never crosses or touches itself. You can believe the data to meet the following conditions: The polygons don’t intersect with each other, Xiaoming and the Big Boss are located on the edge of the polygon and Xiaoming never located on the vertices of the polygons. Xiaoming and the Big Boss always located on different position.
$C \leq 50, n \leq 50, m\_i \leq 50$.

# Standard Output

For each set of data, the output may be one of the following case: Can’t hit the target.

The shells is fired at a speed of $SP(m/s)$, and successfully hit the target.

In the first case, Xiaoming can’t use his unique skills, to give the Big Boss the final blow. In the second case, Xiaoming successfully hit the Big Boss. He fires shells at a speed of $SP(m/s)$, if $X\_{xiaoming}$ is less than $X\_{boss}$, $SP$ is a positive value else $SP$ is a negative value. the result must be accurate to $4$ decimal places.

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
1
0 0 4 0
4
-1 0
-1 -1
5 -1
5 0
2
0 0 4 0
4
-1 0
-1 -1
5 -1
5 0
4
3 2
3 1
5 1
5 2
2
4 2 0 0
4
-1 0
-1 -1
5 -1
5 0
4
3 2
3 1
5 1
5 2</td><td>The shells are fired at a speed of 6.7961 (m/s), and successfully hit the target.
Can’t hit the target.
The shells are fired at a speed of -5.9867 (m/s), and successfully hit the target.</td></tr></table>


# Constraints



# Note



# Source


