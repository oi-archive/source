
# Content

Building the roads in the shortest time restored the transport facilities of Country X. However, the economy is still under a downturn. After investigating for a long time, Qiqi found that the key point is the high cost of traffic between capital and the other cities.

Now Qiqi wants to find the best reconstruction plan. Best plan must satisfy the following conditions:
1. for each non-capital city, there is exactly one path from capital to it, and the length of this very path should be minimal.
2. after satisfying the first condition, the total length of all roads needed to build is minimal.

Given many optional roads Qiqi can build, please tell him the total length of roads in the best plan. Note that all roads in this problem are **one-way**.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 20$) indicating the number of test cases.

The first line of each test case contains two integers: $N$ $M$, representing the number of cities of Country X, and number of optional roads. The cities are numbered from $1$ to $N$ and the capital is numbered $1$.

Then comes $M$ lines, each gives a road: $x\_i$ $y\_i$ $v\_i$, representing that Qiqi could build a road from $x\_i$ to $y\_i$ and the length of this road is $v\_i$. 

We guarantee there are no multiple roads and self-loops.

$1 \leq N \leq 1000$, $1 \leq M \leq 1000000$.

$1 \leq x\_i, y\_i \leq N$, $1 \leq v\_i \leq 10000$.

# Standard Output

For each test case, print `Case #t: ` first, in which $t$ is the number of the test case starting from $1$. Then output the total length. If Qiqi cannot find a plan, output `-1`.

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
3 3
1 2 1
2 3 1
1 3 2
3 2
1 2 1
3 2 1</td><td>Case #1: 2
Case #2: -1</td></tr></table>


# Constraints



# Note

Huge input/output. Please use `scanf/printf` for `C/C++`.

# Source


