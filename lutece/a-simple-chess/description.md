
# Content

There is a $n\times m$ board, a chess want to go to the position $(n, m)$  from the position $(1, 1)$.

The chess is able to go to position $(x_2, y_2)$ from the position $(x_1, y_1)$, if and only if $x_1, y_1, x_2, y_2$  is satisfied that $(x_2 - x_1)^2+(y_2 - y_1)^2 = 5, ~x_2 > x_1,~ y_2 > y_1$.

Unfortunately, there are some obstacles on the board. And the chess never can stay on the grid where has a obstacle.

I want you to tell me, There are how may ways the chess can achieve its goal.

# Standard Input

The input consists of multiple test cases.

For each test case:

The first line is three integers, $n, m, r, (1\leq n, m\leq 10^{18}, 0 \leq r\leq 100)$, denoting the height of the board, the weight of the board, and the number of the obstacles on the board.

Then follow $r$ lines, each lines have two integers, $x, y(1\leq x\leq n, 1\leq y\leq m)$, denoting the position of the obstacles. please note there aren't never a obstacles at position $(1, 1)$.

# Standard Output

For each test case,output a single line "Case #x: y", where x is the case number, starting from 1. And y is the answer after module $110119$.

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
<tr><td>1 1 0
3 3 0
4 4 1
2 1
4 4 1
3 2
7 10 2
1 2
7 1</td><td>Case #1: 1
Case #2: 0
Case #3: 2
Case #4: 1
Case #5: 5</td></tr></table>


# Constraints



# Note



# Source


