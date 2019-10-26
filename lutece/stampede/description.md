
# Content

You have an $n\times n$ game board. Some squares contain obstacles, except the left- and right-most columns
which are obstacle-free. The left-most column is filled with your $n$ pieces, $1$ per row. Your goal is to
move all your pieces to the right-most column as quickly as possible. In a given turn, you can move
each piece `N`, `S`, `E`, or `W` one space, or leave that piece in place. A piece cannot move onto a square
containing an obstacle, nor may two pieces move to the same square on the same turn. All pieces move
simultaneously, so one may move to a location currently occupied by another piece so long as that piece
itself moves elsewhere at the same time.

Given $n$ and the obstacles, determine the fewest number of turns needed to get all your pieces to the
right-hand side of the board.

# Standard Input

Each test case starts with a positive integer $n$ indicating the size of the game board, with $n\leq 25$.
Following this will be $n$ lines containing $n$ characters each. If the $j^{th}$ character in the $i^{th}$ line is an `X`,
then there is an obstacle in board location $i, j$; otherwise this character will be a `.` indicating no
obstacle. There will never be an obstacle in the $0^{th}$ or $(n-1)^{st}$ column and there will always be at least
one obstacle-free path between these two columns. A line containing a single $0$ will terminate input.

# Standard Output

For each test case output the minimum number of turns to move all the pieces from the left side of the
board to the right side.

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
<tr><td>5
.....
.X...
...X.
..X..
.....
5
.X...
.X...
.X...
.XXX.
.....
0</td><td>Case 1: 6
Case 2: 8</td></tr></table>


# Constraints



# Note



# Source


