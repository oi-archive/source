
# Content

The world is actually neither a disc or a sphere. It is a ring! There are m cities there, conveniently
called $0,1,2,\cdots ,m−1$, and arranged on the ring in the natural order: first $0$, then $1$, then $2$, $\cdots$, then
$m−1$, and then again $0$ (as the world is a ring, remember?). You are given a collection of contiguous
ranges of cities. Each of them starts at some city $x$, and contains also cities $x+1, x+2, \cdots, y −1,y$,
for some city $y$. Note that the range can wrap around, for instance if $m = 5$, then $[3,4,0]$ is a valid
range, and so are $[1]$, $[2,3,4]$, or even $[3,4,0,1,2]$. Your task is to choose a single city inside each
range so that no city is chosen twice for two different ranges.

# Standard Input

The input consists of several lines. The first line contains $1\leq T\leq 20$, the number of test cases.
Each test case consists of a number of lines. The first line contains two integers $1\leq m\leq 10^9$ and
$1\leq n\leq 10^5$ denoting the number of cities and the number of requests, respectively. The next $n
$
lines define the ranges: the $i^{th}$ row contains two integers $0\leq x_i ,y_i < m$ describing the $i^{th}$ range
$[x i ,x i + 1$ mod $m,...,y i ]$.

# Standard Output

For each test case, output one line containing `YES` if it is possible to assign a unique city to each
request, and `NO` otherwise.

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
3 3
0 1
1 2
2 0
200000 3
100000 100000
100001 100001
100000 100001
6 6
0 1
1 2
2 3
3 4
4 5
5 0
6 6
0 0
1 2
2 3
4 4
4 5
5 0</td><td>YES
NO
YES
NO</td></tr></table>


# Constraints



# Note



# Source


