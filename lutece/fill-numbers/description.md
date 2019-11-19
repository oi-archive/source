
# Content

Stephydx invented a new puzzle for you to solve! The puzzle is a matrix with $n$ rows, and each row consists of $m$ grids. Each grid may be empty or have a number in it. But you can assume that there are no more than **TWO** empty grids at each row and column. Now, we want to fill numbers in each empty grid to make the sum of each row, and each column equal to some specific numbers.

You have to find out whether the solution is unique, or more than one, or we have no solutions at all.

# Standard Input

The first line of the input is an integer $T$, indicating the test cases. ($T\leq 50$)

For each test case, there are two numbers $N$ and $M$, indicating the size of the matrix ($1\leq N\leq 500$, $1\leq M\leq 500$). Then $N$ lines follow, each 
consists of $M$ integers, representing $N$ rows of the matrix. If the grid is empty, that number will be $-1$, otherwise the number will always be non-negative and no more than $1000$. 

Then a line with $N$ integers lists the sum we required for each row, from up to bottom. The next line has $M$ integers, listing the sum we required for each column, from left to right.

The absolute value of the required sum of each row and column will not exceed $1000000$.

# Standard Output

For each test case, first print `Case #k: ` first ,in which $k$ represents the case number which starts from $1$, then output a word `Unique`, `More than one`, or `No solution`, as described above.

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
2 2
1 1
-1 -1
2 4
3 3
2 2
1 1
-1 -1
2 5
3 3
2 2
1 1
2 2
2 4
3 3
4 4
1 2 3 4 
1 -1 -1 2
3 -1 -1 4
5 6 7 8
10 6 14 26
10 13 15 18
2 2
1 -1
2 -1
-1 1
3 -3</td><td>Case #1: Unique
Case #2: No solution
Case #3: Unique
Case #4: More than one
Case #5: Unique</td></tr></table>


# Constraints



# Note

Please note that although the numbers that are already filled in the matrix are all non-negative, a solution with negative numbers is still acceptable. Also if a row or a column has no empty grids, the sum of that row or column will always equal to the required sum we gave.

# Source


