
# Content

Given an $n\times n$ matrix $A$, whose elements are either $0$ or $1$. $A\_{ij}$ means the number in the $i\_{th}$ row and $j\_{th}$ column. Initially we have $A\_{ij} = 0$ ($1\leq i, j\leq n$).

We can change the matrix in the following way. Given a rectangle whose upper-left corner is $(x\_1, y\_1)$ and lower-right corner is $(x\_2, y\_2)$, we change all the elements in the rectangle by using `not` operation (if it is a $0$ then change it into $1$ otherwise change it into $0$). To maintain the information of the matrix, you are asked to write a program to receive and execute two kinds of instructions.

1. `C x1 y1 x2 y2` ($1\leq x\_1\leq x\_2\leq n$, $1\leq y\_1\leq y\_2\leq n$) changes the matrix by using the rectangle whose upper-left corner is $(x\_1, y\_1)$ and lower-right corner is $(x\_2, y\_2)$.
2. `Q x y` ($1\leq x, y\leq n$) querys $A\_{xy}$.

# Standard Input

The first line of the input is an integer $X$ ($X\leq 10$) representing the number of test cases. The following $X$ blocks each represents a test case.

The first line of each block contains two numbers $N$ and $T$ ($2\leq N\leq 1000$, $1\leq T\leq 50000$) representing the size of the matrix and the number of the instructions. The following $T$ lines each represents an instruction having the format `Q x y` or `C x1 y1 x2 y2`, which has been described above.

# Standard Output

For each querying output one line, which has an integer representing $A\_{xy}$.

There is a blank line after every test case.

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
2 10
C 2 1 2 2
Q 2 2
C 2 1 2 1
Q 1 1
C 1 1 2 1
C 1 2 1 2
C 1 1 2 2
Q 1 1
C 1 1 2 1
Q 2 1</td><td>1
0
0
1</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by standy. So any mistake here does not imply mistake in the offcial judge data.

# Source


