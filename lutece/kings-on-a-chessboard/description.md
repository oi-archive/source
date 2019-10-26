
# Content

You are given a chessboard of size $x \times y$ and $k$ identical kings, and are asked to place all the kings on the board such that no two kings can attack each other. Two kings can attack each other if they are horizontally, vertically or diagonally adjacent.

![title](/source/lutece/kings-on-a-chessboard/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzE2LzIwMTQwOTAxMTgyOTAxNDEzMzIucG5n.png)

Write a computer program that calculates the number of possible arrangements of the $k$ kings on the given chessboard. Since the number of feasible arrangements may be large, reduce the number modulo $1,000,000,007$.


# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each of the following $T$ lines consists of three integers $x$, $y$ and $k$,separated by one space.

$0 < T \le 50$

$2 \le x, y \le 15$

$1 \le k \le x\times y$

# Standard Output

For each test case, output the number of possibilities modulo $1,000,000,007$.

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
<tr><td>4
8 8 1
7 7 16
7 7 7
3 7 15</td><td>64
1
2484382
0</td></tr></table>


# Constraints



# Note



# Source


