
# Content

ZT loves to paint on papers. One day, he wants to paint every cell on the board whose size is $N \times M$ with black and white. However, the painted board should meet this condition: for every $2 \times 2$ block, there are exactly $W$ white cells and $4 - W$ black cells. To make this problem more interesting, some cells on board have already been colored. How many different boards can ZT paint?

Note that two boards are different if at least one corresponding cell's color is different.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T\leq 50$) indicating the number of test cases.

For each test case there are three integers $N$, $M$, $K$ ($2 \leq N, M \leq 100000$, $0 \leq K \leq 100000$) in a single line, representing the size of board and the number of colored cells. For the following $K$ lines, each line contains two integers $R\_i$, $C\_i$ and a character $S\_i$. It means the cell in the $R\_i^{th}$ row and $C\_i^{th}$ column has been colored in $S\_i$. $1 \leq R\_i \leq N$, $1 \leq C\_i \leq M$, $S\_i$ is `W` or `B` indicating this cell is colored in white or black.

# Standard Output

For each test case, print `Case #t: ` first, in which $t$ is the number of the test case starting from $1$. Then output five integers indicating the number of different colored boards when $W = 0, W = 1, W = 2, W = 3, W = 4$. The result should be modulo by $20120407$.

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
3 3 2
1 1 B
2 2 W</td><td>Case #1: 0 1 4 3 0</td></tr></table>


# Constraints



# Note

The first sample is like this
```
B..
.W.
...
```

# Source


