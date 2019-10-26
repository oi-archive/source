
# Content

Totalfrank has played chess for more than ten years. Recently he invents a chess game named Knight and Rook!

The rule of this game is simple: given a board of size $n\times m$, which has some obstacles on it, you need to calculate the minimum number of steps to move a chessman from a start position to an end position. 

There are two kinds of chessman in this game, one is knight and the other one is rook. In each step, a rook can go vertically or horizontally as long as there is no obstacle on the route, and a knight can only go to $8$ grids which are shown below:

![title](/source/lutece/knight-and-rook/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzgxLzIwMTQwNDExMTk0OTUwNDM2MzkucG5n.png)

Of course, a knight can’t move to a grid which is an obstacle or out of the chess board, neither a rook can.

At the start of the game, you choose a chessman (either a knight or a rook) to put it on the start position. You can switch it to the other one during the game to move to the end position. Switch isn’t considered as one step, but you have at most one chance to switch. Please tell me the minimum number of steps you need to finish this game.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 20$), which stands for the number of test cases you need to solve.

Each test case begins with two integers $n$, $m$ ($1\leq n, m\leq 100$) in the first line indicating the size of the board. Then n lines follow, each line consists of $m$ characters which are:
* `.` : represents an grid which a chessman can step on.
* `#`: represents an obstacle which a chessman cannot step on.
* `s`: represents the start position and there is exactly one `s` on the board.
* `t`: represents the end position and there is exactly one `t` on the board

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then if it’s impossible to reach the end position, just output `-1`. Otherwise, output the minimum number of steps to this question.

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
<tr><td>4
2 3
s..
..t
2 3
s##
.t#
2 3
s#t
...
2 3
s#t
###</td><td>Case #1: 1
Case #2: 2
Case #3: 2
Case #4: -1</td></tr></table>


# Constraints



# Note



# Source


