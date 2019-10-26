
# Content

Yu Zhou likes to play `Go` with Su Lu. From the historical research, we found that there are much difference on the rules between ancient go and modern go.

Here is the rules for ancient go they were playing:
* The game is played on a $8\times 8$ cell board, the chess can be put on the intersection of the board lines, so there are $9\times 9$ different positions to put the chess.
* Yu Zhou always takes the black and Su Lu the white. They put the chess onto the game board alternately.
* The chess of the same color makes connected components(connected by the board lines), for each of the components, if it's not connected with any of the empty cells,
	this component dies and will be removed from the game board.
* When one of the player makes his move, check the opponent's components first. After removing the dead opponent's components, check with the player's components and remove
	the dead components.


One day, Yu Zhou was playing ancient go with Su Lu at home. It's Yu Zhou's move now. But they had to go for an emergency military action. Little Qiao looked at the game board and
would like to know whether Yu Zhou has a move to kill at least one of Su Lu's chess.

# Standard Input

The first line of the input gives the number of test cases, $T$($1\leq T\leq 100$). $T$ test cases follow. Test cases are separated by an empty line. Each test case consist of $9$
lines represent the game board. Each line consists of $9$ characters. Each character represents a cell on the game board. `.` represents an empty cell. `x` represents a
cell with black chess which owned by Yu Zhou. `o` represents a cell with white chess which owned by Su Lu.

# Standard Output

For each test case, output one line containing `Case #x: y`, where $x$ is the test case number (starting from $1$) and $y$ is `Can kill in one move!!!` if Yu Zhou
has a move to kill at least one of Su Lu's components. `Can not kill in one move!!!` otherwise.

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

.......xo
.........
.........
..x......
.xox....x
.o.o...xo
..o......
.....xxxo
....xooo.

......ox.
.......o.
...o.....
..o.o....
...o.....
.........
.......o.
...x.....
........o</td><td>Case #1: Can kill in one move!!!
Case #2: Can not kill in one move!!!</td></tr></table>


# Constraints



# Note

In the first test case, Yu Zhou has $4$ different ways to kill Su Lu's component.

In the second test case, there is no way to kill Su Lu's component.

# Source


