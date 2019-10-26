
# Content

*Warning: This problem might be VERY LONG. But it is actually not a very hard problem. Be patient, we have tried our best to make it apprehensible.*
 
####Game Description

In this problem we just describe a game which kennethsnow has recently played. The game is played on a rectangular board with length and width no more than $6$. The board is given to you by $n$ strings, each with length $m$, describing a $n\times m$ board.

####Board Description

There are FOUR kinds of squares on the board:
1. `Green Bricks`. They are shown in the string as `1`.
2. `Red Bricks`. They are shown in the string as `2`. 
3. `Empty Square`. They are shown in the string as a dot `.`.
4. `Magic Bricks`. They are shown in the string as `?`.

![title](/source/lutece/just-a-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjg4LzIwMTQwMzE4MTQxMzA5NzM5NS5qcGc=.jpg)

*An example of Magic Bricks, showed in white*

There will be no more than 15 Bricks on the board.

####Features Description

Besides those four kinds of squares, some positions have special features. They will be given in the input independently. Please note that the features belong to positions only, not the squares or bricks at that position. 
There are two features:
1. `Destination`. There will be no more than one position with that feature.<br/>
![title](/source/lutece/just-a-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjg4LzIwMTQwMzE4MTQxNDU1ODgwNi5qcGc=.jpg)<br/>
*An example of Destination: (Showed as a STAR)*
2.  `Reverse`. There will be no more than two positions with that feature.

Their detail abilities will be talked later.

####To play the game

The game is processed by moves. 

A single move is legal when some conditions are satisfied.
1. You choose an empty square, and count the number of bricks neighboring that square. (Four directions: `Up`, `Down`, `Left`, `Right`, if there are any)
2.  
  1. When there are no magic bricks:<br/>
Count the number of Green Bricks and the number of Red Bricks. If both of them are less than two, then this move is illegal. If their numbers are equal, it is also illegal. Otherwise, we have a color of which the bricks share a larger number. We call that color a `Dominating Color`.
  2. When there are magic bricks:</br>
Count as step $2.1$. When there are no Green Bricks and Red Bricks, the move is illegal. Otherwise, if there are equal or more Green Bricks than Red Bricks, turn the color of magic bricks into Green. Otherwise turn the color of magic bricks into Red. Then decide `Dominating Color` as step $2.1$. <br/>
![title](/source/lutece/just-a-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjg4LzIwMTQwMzE4MTQyMzUwODk4Ny5wbmc=.png)<br/>
*If we choose the empty square as pointed, the Magic Bricks will turn Red. The first image above is the initial state of this image.*<br/>
![title](/source/lutece/just-a-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjg4LzIwMTQwMzE4MTQyNDI4OTc4OC5qcGc=.jpg)<br/>
*If we choose the empty square as pointed, the Magic Bricks will turn Green. The first image above is the initial state of this image.*
3. If all the steps above are legal, clear the neighboring Bricks with the `Dominating Color`. Here `clear` means turn those positions into `Empty Squares`.
4. After clearing, turn the Empty Square you choose into Green or Red Brick. There might be two conditions: If the position you choose has the feature `Reverse`, the color of the Brick will be the one different from `Dominating Color`, otherwise the color will be the `Dominating Color`.

####To win the game

As you can see, after each move, the number of Bricks on the board will decrease. (If you don’t understand this, please read the description again or ask on BBS for a clarification!). So if you play well, there will be a time when there is only one Brick on the board. If you have no legal moves before you reach this state, you’ve already lost.
* If you reach this state, and there are no positions with feature `Destination`, you win.
* If you reach this state, and there is a position with feature `Destination`, and your last Brick is at that position, you win.
* Otherwise, you lose.

####Problem Description

Thanks a lot for reading this problem! It took me an hour to write it…

You are given the initial board, and all the positions with some features. Determine the minimum step to win the game, it is guaranteed all the game in the test cases will have a solution.

# Standard Input

The first line of the input contains a single number $T$, indicating the number of test cases. ($T\leq 30$)

For each test case, first line has two integers $n$ and $m$, describing the size of the board. ($4\leq n, m\leq 6$). Then given the board in detail, with $n$ lines, each has a length-$m$ string.

Then two numbers $x$ and $y$ are given. Which is the position with feature `Destination` as $(x, y)$ ($0\leq x < n, 0\leq y < m$). If there are no such position, both of them will be $-1$.

Then a single integer $p$ ($p\leq 2$), which is the number of `Reverse` positions. Then $p$ lines each with two numbers $x$ and $y$, describing the position $(x, y)$ ($0\leq x < n, 0\leq y < m$).

There is a blank line before each test case.

# Standard Output

For each test case, output `Case #x: ` first, where $x$ is the case number. Then output the minimum step to win the game.

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

5 5
..1..
.1.1.
.....
..2..
.....
-1 -1
1
1 2</td><td>Case #1: 2</td></tr></table>


# Constraints



# Note

The Sample Input can be solved in this way:

*Initial Board*

![title](/source/lutece/just-a-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjg4LzIwMTQwMzE4MTQyNzEwOTk1OS5qcGc=.jpg)

*Step 1* 

![title](/source/lutece/just-a-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjg4LzIwMTQwMzE4MTQyNzM4MTk0MTAuanBn.jpg)

*Step 2*

![title](/source/lutece/just-a-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjg4LzIwMTQwMzE4MTQyNzU2NDk1MTEuanBn.jpg)

# Source


