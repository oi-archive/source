
# Content

There is a rectangular city with $N$ rows and $M$ columns, and every grid has some people living there. Now Alibaba wants to choose some grids to build $K$ service stations. The best way to build service stations is to make the largest distance among all distances between a grid and its nearest service station as short as possible. The distance between two grids $(x\_1, y\_1)$ and $(x\_2, y\_2)$ is $\max(|x\_1-x\_2|, |y\_1-y\_2|)$, where $|x|$ is the absolute value of $x$. Now it’s you work to build service stations optimally.

# Standard Input

The first line of input contains an integer $T$ ($T\leq 1000$), which is the number of data sets that follow.

Every test case consists of three integers $N$, $M$, $K$, which are specified before.
$1\leq N, M, K\leq 1000000000$.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then output the largest distance among all distances between a grid and its nearest police station while you build police stations optimally.

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
1 1 1
2 2 1
3 3 1</td><td>Case #1: 0
Case #2: 1
Case #3: 1</td></tr></table>


# Constraints



# Note



# Source


