
# Content

Under the guide of CC, flower fairies left thousand of mountains and rivers behind and got close to the paradise after several months. However, they have to pass through a weird world to enter the paradise as soon as possible so that the monster Littlefatcat would never find the place where they want to go.

This world has two sides and anytime one can only be in either of the two sides. The side fairies are in is filled with light and the other side is full of rock. The world is divided into an $N\times M$ grid. Each cell belongs to either side. In the example below, light cells are white and rock cells are black.

Fairies can use magic to reverse this world. When they do this, the whole world will be upside down and things in each side will flow to its opposite, that is to say, light cells turn to rock ones, and vice versa. What’s more, flower fairies would enter the opposite side with the line they stand on unchanged. The only way connecting the world to paradise is an exit. When they get to the exit, they succeed in passing through this weird world.

![.*](/source/lutece/pass-through/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE5LzIwMTQwMjAxMTIyNDAyMTcxMi5wbmc=.png)

Fairies can move to the left adjacent cell or the right one. Also, they can jump to the cell just above their current cell or above the cell on the left or on the right. They can’t get into a black grid or move outside of this world. 

![.*](/source/lutece/pass-through/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE5LzIwMTQwMjAxMTIyNDM1Nzg0My5wbmc=.png)

After each move, fairies will fall down vertically until they reach a rock cell or the exit, or the edge of this world. Note that the magic to reverse the world can only be used only when their feet touch the rock cell. Each move or jump takes one second, so does using magic. The time for fairies falling down can be ignored.

In order to get to the exit as soon as possible, CC would choose the optimal strategy. Do you know the minimum second fairies need to pass through this weird world?

# Standard Input

The first line of the input is $T$ (no more than $2000$), which stands for the number of test cases you need to solve. 

Each test case begins with two integers $N$, $M$ ($0 < N, M\leq 50$), which describe the height and width of the world.

The next line contains four integers: $s\_x$, $s\_y$, $e\_x$, $e\_y$, representing the coordinates of the start position of fairies and the exit. It is guaranteed that at the beginning fairies are in a light cell and stand on a rock cell or the edge. The coordinate of upper left corner is $(0, 0)$, and of the lower right corner is $(N – 1, M – 1)$. Also, $0 \leq s\_x, e\_x < N$, $0\leq s\_y, e\_y < M$ and $(s\_x , s\_y)$ is different from $(e\_x , e\_y)$.

Then followed $N$ lines each line contains $M$ characters describe the map, each character will either be`R` (rock) or `_` (light).

# Standard Output

For each case, print an integer $t$ on a single line, which is the minimum second fairies need to pass through this world. If they can never get out, print $-1$ instead.

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
5 2
3 0 2 1
R_
__
__
__
RR
4 6
0 5 2 5
R_R___
_R__RR
___RR_
RR___R
10 10
0 0 3 7
_R_RRRRR_R
R___R_R___
RR_R___R_R
R_RRR_R_RR
_R___RR___
_R_RRR_R_R
R_______RR
_RRRRR_R_R
R______RRR
RR_RRRRR__</td><td>1
-1
26</td></tr></table>


# Constraints



# Note



# Source


