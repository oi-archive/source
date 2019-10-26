
# Content

There are $N$ points in total. Every point moves in certain direction and certain speed. We want to know at what time that the largest distance between any two points would be minimum. And also, we require you to calculate that minimum distance. We guarantee that no two points will move in exactly same speed and direction.

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

For each test case, first line has a single number $N$ ($N\leq 300$), which is the number of points.

For next $N$ lines, each come with four integers $X_i$, $Y_i$, $VX_i$ and $VY_i$ ($-10^6 \leq X_i$, $Y_i \leq 10^6$, $-10^2 \leq VX_i$, $VY_i \leq 10^2$), ($X_i$, $Y_i$) is the position of the $i^{th}$ point, and ($VX_i$, $VY_i$) is its speed with direction.
That is to say, after $1$ second, this point will move to ($X_i + VX_i$, $Y_i + VY_i$).

# Standard Output

For test case $X$, output `Case #X: ` first, then output two numbers, rounded to $0.01$, as the answer of time and distance.

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
<tr><td>2
2
0 0 1 0
2 0 -1 0
2
0 0 1 0
2 1 -1 0</td><td>Case #1: 1.00 0.00
Case #2: 1.00 1.00</td></tr></table>


# Constraints



# Note



# Source


