
# Content

Babs sells boxes and lots of them. All her boxes are rectangular but come in many different sizes. Babs wants to create a really eye-catching display by stacking, one on top of another, as many boxes as she can outside her store. To maintain neatness and stability, she will always have the sides of the boxes parallel but will never put a box on top of another if the top box sticks out over the bottom one. For example, a box with base $5$-by-$10$ can not be placed on a box with base $12$-by-$4$.

Of course the boxes have three dimensions and Babs can orient the boxes anyway she wishes. Thus a $5$-by-$10$-by-$12$ box may be stacked so the base is $5$-by-$10$, $5$-by-$12$, or $10$-by-$12$.

For example, if Babs currently has $4$ boxes of dimensions $2$-$2$-$9$, $6$-$5$-$5$, $1$-$4$-$9$, and $3$-$1$-$1$, she could stack up to $3$ boxes but not all four. (For example, the third box, the first box, then the last box, appropriately oriented. Alternatively, the second box could replace the third (bottom) box.)

Babs’ stock rotates, so the boxes she stacks outside change frequently. It’s just too much for Babs to figure out and so she has come to you for help. Your job is to find the most boxes Babs can stack up given her current inventory. Babs will have no more than $10$ different sized boxes and will use at most one box of any size in her display.

# Standard Input

A positive integer $n$ ($n\leq 10$) will be on the first input line for each test case. Each of the next n lines will contain three positive integers giving the dimensions of a box. No two boxes will have identical dimensions. None of the dimensions will exceed $20$. A line with $0$ will follow the last test case.

# Standard Output

For each test case, output the maximum number of boxes Babs can stack using the format given below.

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
2 2 9
6 5 5
1 4 9
3 1 1
3
2 4 2
1 5 2
3 4 1
0</td><td>Case 1: 3
Case 2: 3</td></tr></table>


# Constraints



# Note



# Source


