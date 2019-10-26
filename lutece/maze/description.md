
# Content

You are given a special Maze described as an $n\times m$ matrix, please find the shortest path to reach $(n,m)$ from $(1,1)$

# Standard Input

The first line of the input is an integer $T$ ($T\leq 100$), which stands for the number of test cases you need to solve.

Each test case begins with two integers $n$, $m$ ($1\leq n, m\leq 250$) in the first line indicating the size of the board. Then n lines follow, each line contains m numbers either $0$ or $1$ which are:
* $0$ : represents a grid on which you can step.
* $1$ : represents a wall.

# Standard Output

For every test case, you should output `Case #k: ` first, where k indicates the case number and starts at $1$. If it’s impossible to reach the end position, just output `-1`. Otherwise, output the minimum number of steps to solve this problem.

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
0 1 0 0 0
0 1 0 1 0
0 0 0 0 0
0 1 1 1 0
0 0 0 1 0</td><td>Case #1: 8</td></tr></table>


# Constraints



# Note



# Source


