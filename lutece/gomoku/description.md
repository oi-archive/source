
# Content

Gomoku is an abstract strategy board game. Named Gobang or Five in a Row as well, it is traditionally played with pieces of two colors (black and white) on a board (with n×m intersections). Once a piece is placed, it is not allowed to be moved or removed from the chessboard, and thus, Gomokuis also widely played as a paper-and-pencil game.
The rules of the game are quite simple. The black plays first, and two players will alternate in placing a stone of their own color on an empty intersection. The winner is the first one who gets an unbroken row of five stones horizontally, vertically, or diagonally.

Claire and ykwd always play games together, and to day it turns out to be Gomoku.Claire always uses the white stone while ykwd uses the black one. For fairness, they determine who plays first by the finger-guessing game-“Stone, Scissors and Cloth”.Therefore, both Claire and ykwd have chances to be the first player. If some one wins, they end the game immediately and restart another Gomoku. 

But ykwd becomes lazier recently, for which Claire figures out a problem about Gomoku. Claire randomly draws some stages of the game, and forces ykwd to answer whether it is possible to reach, and if so, who wins.He has to solve it as soon as possible,otherwise ykwd would stand on his knees on the keyboard.Help him!

# Standard Input

There are multiple cases, ended by EOF. Each case stands for some stages of Gomoku. 

The first line of each case contains two integers $n$ and $m$ ($1\le n,m\le 100$), which indicates that the size of the board is $n\times m$. Then $n$ lines followed, each with a string of length $m$. The white stone is denoted by `1`,and the black stone is denoted by `2`, while the empty place is denoted by `.`(a full period).

# Standard Output

For each case, if it is impossible to arrive at such a stage according to the rules, output `fault`. Otherwise, if Claire wins, then output `white`; if ykwd wins, output `black`; or else output `other`.

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
<tr><td>10 10
..........
..........
...1......
...2......
..........
..........
..........
..........
..........
..........
10 10
..........
..........
..........
...1......
..1.......
..1.2.....
..........
..........
..........
..........</td><td>other
fault</td></tr></table>


# Constraints



# Note



# Source


