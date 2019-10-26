
# Content

For a positive integer, we define its weight as follows:

First we denote it in $2$ base as $b\_nb\_{n-1}\cdots b\_1b\_0$, with the most significant bit at the leftmost position. The weight of the integer is the number of pairs $(b\_i,b\_j)$, where $i > j$, and $b\_i > b\_j$. For example, `10` ($10$ base) = `1010` ($2$ base), so the weight of $10$ is $3$.

In this problem, we will give you some positive integers’ weights, and for every weight, you should find the smallest positive integer whose weight is equal to it.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 1000$), which stands for the number of test cases you need to solve.

Every test case is a single integer $w$ ($1\leq w\leq 10^9$), indicates the weight of a positive integer.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then output the answer. As the answer may be very large, you only need to tell me the remainder while it divides $1000000007$. See sample for more details.

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
1
2
3
4</td><td>Case #1: 2
Case #2: 4
Case #3: 8
Case #4: 12</td></tr></table>


# Constraints



# Note



# Source


