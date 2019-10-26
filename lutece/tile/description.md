
# Content

Squares and rectangles fascinated the famous Dutch painter Piet Mondriaan. One night, after producing the drawings in his `toilet series` (where he had to use his toilet paper to draw on, for all of his paper was filled with squares and rectangles), he dreamt of filling a large rectangle whose some cells can't be filled with small rectangles of width $2$ and height $1$ in varying ways.

Expert as he was in this material, he saw at a glance that he'll need a computer to calculate the number of ways to fill the given large rectangle whose dimensions were integer values, as well. Help him, so that his dream won't turn into a nightmare!

# Standard Input

On the first line of the input is a single positive integer $C$, telling the number of test scenarios to follow. The first line of each test case contains three integer numbers: the height $h$ and the width $w$ of the large rectangle and the number of prohibit positions $n$. Then followed with $n$ lines. Each line contains two integers row and col, meaning the cell in (row, col) can't be filled. Note $1 \leq row \leq h$ and $1 \leq col \leq w , 1 \leq h,w \leq11$.

# Standard Output

For each test case, output the number of different ways the given rectangle can be filled with small rectangles of size 2 times 1. Assume the given large rectangle is oriented, i.e. count symmetrical tilings multiple times.

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
<tr><td>3
2 2 0
2 3 2
1 1
2 3
11 10 0</td><td>2
1
3852472573499</td></tr></table>


# Constraints



# Note

Case $1$:a $2 \times 2$ rectangle with no obstacle ,you put $2$ $2 \times 1$ rectangles vertically or horizontally to fill it,so there're $2$ ways in total.

Case 2:a rectangle as below (`x` stands for obstacle and `o` stands for available grid):
```
xoo
oox
```
only one way to fill it(grid with the same number belongs to one $2 \times 1$ rectangle)
```
x11
22x
```

# Source


