
# Content

The eight-puzzle is a famous problem which consists of eight sliding tiles, numbered by digits from $1$ to $8$, placed in a $3\times 3$ squared board of nine cells. 

One of the cells is always empty, in each step, any adjacent (horizontally and vertically) tile can be moved into the empty cell, so that we can change the board's state from one to another. 

We say two states'distance is the minimum steps you need to change a state into another. And we say two states are the same if and only if all the elements in the nine cells are corresponsive same, so the distance with the same states is $0$. 

So now, your mission comes, give you an initial state,and a number $D$, you have to find how many different states that has the distance of $D$ from the initial state.

# Standard Input

In the first line, you will get a number $T$ denote the number of the test cases. ($1\leq T\leq 1000$)

Follow are the $T$ cases

Each of the first $3$ lines of each case contains $3$ numbers, so the $3\times 3$ matrix denote the initial state.

The $4\_{th}$ line contains a number $M$ ($1\leq M\leq 1000$) denotes the number of queries in this test case.

The next $M$ lines, each contains a number denotes $D$ ($0\leq D\leq 9!$) as described above.

# Standard Output

For each query, you should output a line with a number denotes the number of different states that 
has the distance of $D$ from the initial state.

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
0 1 2
3 4 5
6 7 8
2
1
2
1 2 3
4 0 5
6 7 8
1
1</td><td>2
4
4</td></tr></table>


# Constraints



# Note

Huge input, please use `scanf/printf` instead of `cin/cout`

# Source


