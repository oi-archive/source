
# Content

Yi Sima was one of the best counselors of Cao Cao. He likes to play a funny game himself. It looks like the modern Sudoku, but smaller.

Actually, Yi Sima was playing it different. First of all, he tried to generate a $4\times 4$ board with every row contains $1$ to $4$, every column contains $1$ to $4$.
Also he made sure that if we cut the board into four $2\times 2$ pieces, every piece contains $1$ to $4$.

Then, he removed several numbers from the board and gave it to another guy to recover it. As other counselors are not as smart as Yi Sima, Yi Sima always made sure that the
board only has one way to recover.

Actually, you are seeing this because you've passed through to the Three-Kingdom Age. You can recover the board to make Yi Sima happy and be promoted. Go and do it!!!

# Standard Input

The first line of the input gives the number of test cases, $T$($1\leq T\leq 100$). $T$ test cases follow. Each test case starts with an empty line followed by $4$ lines.
Each line consist of $4$ characters. Each character represents the number in the corresponding cell (one of `1`, `2`, `3`, `4`). `*` represents that number was removed by Yi Sima.

It's guaranteed that there will be exactly one way to recover the board.

# Standard Output

For each test case, output one line containing `Case #x:`, where $x$ is the test case number (starting from $1$).
Then output $4$ lines with $4$ characters each. indicate the recovered board.

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

****
2341
4123
3214

*243
*312
*421
*134

*41*
**3*
2*41
4*2*</td><td>Case #1:
1432
2341
4123
3214
Case #2:
1243
4312
3421
2134
Case #3:
3412
1234
2341
4123</td></tr></table>


# Constraints



# Note



# Source


