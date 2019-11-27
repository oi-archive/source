
# Content

There is a police and a thief in an $n\times m$ chessboard, whose initial position is $(x\_p, y\_p)$ and $(x\_t, y\_t)$. They move in turns. In each turn, one of the them must move to a neighboring grid(two grid are neighbored if they share a same edge). None of them can move out of the grid. When the police and the thief move into the same grid, the game ends and the thief was caught. Now you know the position of each other and who moves first, please figure out whether the thief would be caught if they both move wisely.

# Standard Input

In the first line, an integer $T$ is given indicating the number of test cases.

For each case, you can get two integers $n$ and $m$ in the first line. ($1\leq n,m\leq 10^3$);

The second line contain four integers $X\_p,Y\_p,X\_t,Y\_t$. ($0\leq X\_p,X\_t < n, 0\leq Y\_p,Y\_t < m$)

$(X\_p, Y\_p)$ is the initial position for the police, $(X\_t, Y\_t)$ is the initial position for the thief.

The third line contain a string `police` or `thief`，it means that which one takes the first step.

# Standard Output

For each case, output the answer (`YES`or `NO`) in a line.

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
3 3
0 1 1 2
thief</td><td>YES</td></tr></table>


# Constraints



# Note



# Source


