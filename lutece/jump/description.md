
# Content

![title](/source/lutece/jump/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzgwLzIwMTQwNDExMTk0NTIyMDAzMzgucG5n.png)

Recently, Standy hooked on a game. At first, he stands on the top of the board and he can jump to any grid in the $1\_{st}$ row with same probability. Then for every step, he can jump left-down, right-down or down with the given probability. (And he may even jump out of the board.) Some grids are traps while others are flats. When Standy jumps to the traps or out of the board, he will go back to the start again. When he reached the last row, he can easily jump to the end with a step. Note that he can’t jump out of board from the start to the $1\_{st}$ row or from the last row to the end.

Now Standy would like to know the expectation of the number of steps to reach the end.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 100$), which stands for the number of test cases you need to solve.

Every test case begins with two integers $R$ and $C$ ($1\leq R\leq 10, 1\leq C\leq 1000$) indicating the number of rows and columns. 

The second line contains two integers $P\_L$ and $P\_R$ ($0\leq P\_L, P\_R\leq 10, 0\leq P\_L+P\_R\leq 10$). And the probability of jump left-down and right-down are $\frac{P\_L}{10}$ and $\frac{P\_R}{10}$ (so the probability of jump down is $\frac{10-P\_L-P\_R}{10}$).

Then $R$ lines follow. Every line contains $C$ characters. The $j\_{th}$ character in the $i\_{th}$ row represents the state of the corresponding grid, `O` is flat and `X` is trap.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then the expected jumps rounded to $3$ digits after the decimal point. If he can’t reach the end, just output `INF` (without quotes).

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
1 3
3 3
XOX
1 1
10 0
X
2 4
3 5
XOXO
OXOX</td><td>Case #1: 4.000
Case #2: INF
Case #3: 6.455</td></tr></table>


# Constraints



# Note



# Source


