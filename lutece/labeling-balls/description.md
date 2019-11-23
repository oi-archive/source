
# Content

Windy has N balls of distinct weights from $1$ unit to $N$ units. Now he tries to label them with $1$ to $N$ in such a way that: 

1. No two balls share the same label.
2. The labeling satisfies several constrains like `The ball labeled with a is lighter than the one labeled with b`.

Can you help windy to find a solution?

# Standard Input

The first line of input is the number of test case. The first line of each test case contains two integers, $N (1 \leq N \leq 200)$ and $M (0 \leq M \leq 40,000)$. The next $M$ line each contain two integers $a$ and $b$ indicating the ball labeled with a must be lighter than the one labeled with $b. (1 \leq a, b \leq N)$ There is a blank line before each test case.

# Standard Output

For each test case output on a single line the balls' weights from label $1$ to label $N$. If several solutions exist, you should output the one with the smallest weight for label $1$, then with the smallest weight for label $2$, then with the smallest weight for label $3$ and so on $\cdots$ If no solution exists, output `-1` instead.

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

4 0

4 1
1 1

4 2
1 2
2 1

4 1
2 1

4 1
3 2</td><td>1 2 3 4
-1
-1
2 1 3 4
1 3 2 4</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by allenlowesy. So any mistake here does not imply mistake in the offcial judge data.

# Source


