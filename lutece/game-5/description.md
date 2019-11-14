
# Content

![title](/source/lutece/game-5/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDg1LzIwMTQwODIyMjM0NjIyMzAzMzAucG5n.png)

Today I want to introduce an interesting game to you. Like eight puzzle, it is a square board with $9$ positions, but it filled by $9$ numbered tiles. There is only one type of valid move, which is to rotate one row or column. That is, three tiles in a row or column are moved towards the head by one tile and the head tile is moved to the end of the row or column. So it has $12$ different moves just as the picture left. The objective in the game is to begin with an arbitrary configuration of tiles, and move them so as to get the numbered tiles arranged as the target configuration.

![title](/source/lutece/game-5/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDg1LzIwMTQwODIyMjM0NjI4MDI3MzEucG5n.png)

Now the question is to calculate the minimum steps required from the initial configuration to the final configuration. Note that the initial configuration is filled with a permutation of $1$ to $9$, but the final configuration is filled with numbers and `*` (which can be any number).

# Standard Input

The first line of input contains an integer $T$ ($T\leq 1000$), which is the number of data sets that follow.

There are $6$ lines in each data set. The first three lines give the initial configuration and the next three lines give the final configuration.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then the fewest steps needed. If he can’t move to the end, just output `No Solution!` (without quotes).

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
1 2 3
4 5 6
7 8 9
1 2 3
4 5 6
7 9 8
1 2 3
4 5 6
7 8 9
8 * 9
5 3 7
2 * *</td><td>Case #1: No Solution!
Case #2: 7</td></tr></table>


# Constraints



# Note



# Source


