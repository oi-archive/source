
# Content

Loneknight is finding treasures in a maze. He is so greedy that he always takes away all the treasure he can reach. Now, he has a map for the maze, and he want to know the maximum of treasure he can get. Please help him calculate this value. Note that in every step, Loneknight can only move up, down, left, or right, if the target place is not a wall. Moreover, he can't move out of the maze, or you may assume that there is a wall suround the whole maze.

# Standard Input

The input consists of several test cases. Each test case start with a line containing two number, $n, m(1 < n, m \leq 1000)$, the rows and the columns of grid. Then $n$ lines follow, each contain exact m characters, representing the type of block in it. (`.` for empty place, `X` for loneknight, `*` for treasure, `#` for wall). Each case contain exactly one `X`. The input end with EOF.

# Standard Output

You have to print the maximum number of treasures loneknight can get in a single line for each case.

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
<tr><td>4 4
*...
.X..
....
...*

4 4
*#..
#X..
....
...*</td><td>2
1</td></tr></table>


# Constraints



# Note



# Source


