
# Content

ZT loves to paint on papers. One day, he wanted to paint every cell in the board whose size is $N \times M$ with black and white. However, the painted board should meet this condition: for every $a$, $b$, $c$, $d$ where $0 \leq a < c < N$ and $0 \leq b < d < M$, the cells $(a, b)$, $(a, d)$, $(c, b)$, $(c, d)$ are not in the same color. How many different boards can ZT paint?

Note that two boards are different if at least one corresponding cell's color is different.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T\leq 300$) indicating the number of test cases.

For each test case there are two integers $N$ and $M$ ($1 \leq N, M \leq 100$) in a single line, representing the size of board.

# Standard Output

For each test case, print `Case #t: ` first, in which t is the number of the test case starting from $1$. Then output the number of different colored board. **The result should be modulo by $20120402$.**

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
2 2
2 3
3 3
1 40</td><td>Case #1: 14
Case #2: 44
Case #3: 156
Case #4: 12140084</td></tr></table>


# Constraints



# Note

For the first sample, we can color four cells with black or white, except two cases (all black and all white).

# Source


