
# Content

Elfness is interested in playing a maze game, the aim of the game is to reach destination point from a start point on a grid map with two kinds of grid: `.` means you can freely get to this grid, `#` means you can’t get to this grid, to make it harder, elfness think there must be exactly one path between any two connected point, or it becaome easy and lose fun,.Moving from one grid to an adjacent grid costs one unit time. As a good gamer, elfness always chooses a way that cost least time. Now, elfness is facing a different maze without destination and start point, so he must determine a start point and an end point by himself, and to challenge himself, he wants to choose two points that can reach each other with their shortest distance as long as possible, but the question is if he calculates the distance by himself, he will know the path, and he has no interests in playing this maze anymore. So he need you to help him calculate the maximum distance.

Notice:if the two points we choose as start point and destination is same point, then the distance is $0$.

# Standard Input

In the first line of input there is an integer $T$, meaning there is $T$ test cases.

For each test case, the first line contains two integers $m$ and $n$ ($2\leq n,m\leq 1000$), which means the maze has $m$ columns and $n$ rows. Then $n$ lines follows, each line contains exactly m characters, describing the maze.

# Standard Output

For each test case, first output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then for each test case output the maximum distance in a single line.

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
3 2
...
.#.
3 3
.#.
.#.
.#.</td><td>Case #1:
4
Case #2:
2</td></tr></table>


# Constraints



# Note



# Source


