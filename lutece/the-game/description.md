
# Content

A game of Renju is played on a board which has ten rows and ten columns by a player. The game has at most ten kind of stones which can be distinguished by their colours. The stones are placed on the grids on the board.

![title](/source/lutece/the-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjA3LzIwMTQwODI4MTE0MDE3NDE4MjUuanBn.jpg)

There are several stones on the board at the begin of the game. Two grids which have the same edge are called neighboured. The stone just can move to its neighboured empty grid in one step. At every move, the player just can pick a stone on the board and move it to another empty grid with any number of steps. After the player makes a move , if there is not less than five stones of the same color consecutively along a horizontal, vertical , or diagonal grids, then the consecutive stones disappear and the player get the score which is the number of the disappeared stones. Notice that if there is more than one consecutively stones that can satisfy the condition, they can disapear at the same time. As Sample $1$ shows, all the stones of the color $1$ disappear in a move.

# Standard Input

There are at most $30$ cases, end by EOF. Each case consists of ten rows, each having ten characters. Every kind of stone is denoted by a digit (from $0$ to $9$). A empty grid is denoted by the character `.`. After each case, there is a blank line.

# Standard Output

For each case, print the case number (starting from $1$), as the format shown in the Sample Output. If the stones which can disappear still stay on the board , then print `Waiting!` to ask the player to wait. If there aren’t stones which can disappear on the board, print the maximal score the player can get in a move.Print a blank line between two consecutive cases.

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
<tr><td>..........
..........
..........
..........
..1...1...
...1.1....
...1......
...1.1....
..1...1...
..........

..........
..........
..........
..........
..1...1...
...1.1....
....1.....
...1.1....
..1...1...
..........</td><td>Case #1: 9

Case #2: Waiting!</td></tr></table>


# Constraints



# Note



# Source


