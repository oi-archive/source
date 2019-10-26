
# Content

Tomb raiders are used to explore complex labyrinths searching treasures. Nowadays, they do it more effectively with the help of hi-tech. However, a team of Chinese tomb raiders have found labyrinths so complex that they can't handle them using their usual techniques. These labyrinths are made of cells, many of them with traps. If one moves into a cell with a trap, then the trap gets triggered. Moreover, if a trap gets triggered, its cell becomes blocked, and cannot be used anymore in a path. To make things worse, they have discovered that traps may have effects at a distance on other traps: if one triggers a trap, then traps associated to it also become triggered. They also discovered that the association between traps comes from a `domination ordering` defined on trap kinds, in such a way that triggering a trap of kind a causes all traps of kind `less than or equal to` a in the domination ordering to become also triggered. You are asked to write a program that given a labyrinth such as this, indicates the minimum number of moves needed to reach the end position from the start position. A move consists in going up, down, left or right (no diagonal moves).

# Standard Input

The input file contains several test cases, each of them as described below.

The input contains the domination ordering on the trap kinds, the map, and the start and end positions. The first line of the input contains a string with $26$ distinct characters defining the domination order of the trap kinds. The first character indicates the weakest trap kind (that only triggers its own kind), the last character is the strongest (that triggers traps of all kinds). The second line contains two integers that indicate the width ($w$) and height ($h$) of the map, where $h\times w$ do not exceed $40000$. The following $h$ lines of the input contain $w$ symbols that define the cells of the map (separated by an empty space). The following codes are used: `x` represents a cell with solid wall, a symbol alpha from `A` to `Z` identifies a cell containing a trap of kind alpha, and `o` represents an empty cell. The two last lines define the coordinates of the start and end positions, with two integers for the $x$ (column) and $y$ (line) coordinates in the grid, starting from $0$.

# Standard Output

For each test case.

If the input describes a problem with a solution, then the output must be an integer in a single line indicating the minimum number of moves needed to reach the end position from the start position. If no solution exists, then the output should contain just `IMPOSSIBLE` in a single line.

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
<tr><td>ZYXWVUTSRQPONMLKJIHGFEDCBA
8 8
x x x x o x x x
x o o C o o o x
x A x x x x D x
x o o o o o o x
x x x o x x x x
x o o B o o o x
x A x x x B x x
o o o o o o o o
4 0
4 7</td><td>17</td></tr></table>


# Constraints



# Note



# Source


