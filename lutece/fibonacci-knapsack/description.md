
# Content

We have $N$ items, each with a specified weight and cost, and a bag that can carry a specified maximum weight. We want to place a subset of these items into the bag such that the total cost is maximized.

In this problem, the weights of the items are all Fibonacci numbers.

The first two Fibonacci numbers are $1$ and $2$. Each successive number is obtained by adding together the two previous numbers. Thus, the first Fibonacci numbers are $1, 2, 3, 5, 8, 13, \cdots $

# Standard Input

The first line contains an integer $T$ indicating the number of test cases.($1\leq T\leq 20$)

The first line of each test case contains two integers $N$ and $W$ ($1\leq N\leq 50$), the number of items and the maximum weight that the bag can carry. Each of the following $N$ lines contains two integers $w\_i$ and $c\_i$($1\leq w\_i,c\_i\leq 10^{16}$, wi will be a Fibonacci number), indicating the weight and cost of each item.

# Standard Output

You should output one line for each test case, containing the case number followed by the maximum total cost of the subset of items that can fit into the bag.

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
3 15
5 18
2 10
13 24
1 2
3 10</td><td>Case 1: 34
Case 2: 0</td></tr></table>


# Constraints



# Note



# Source


