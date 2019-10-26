
# Content

There is a country with $N$ cities, there are roads between some pairs of cities.

For every pair of cities, there is exactly one path between them, on which there are no cities passed more than once.

So it is obvious that there are $N-1$ roads and $\frac{N(N-1)}{2}$ paths.

The cities number from $1$ to $N$, and each road has a length $0$ or $1$.

The length of the path is the sum of the length of roads on it.

A path is prime if and only if the length of the path is a prime number.

How many prime paths in the country?

# Standard Input

The first line contains one integer $N$.

For the next $N-1$ lines, each line contains three integers $u, v, w$, meaning that there is a road with length $w$ between $u^{th}$ city and $v^{th}$ city.

$1\leq N\leq 10^5, 1\leq u, v\leq N, w\in \lbrace 0, 1 \rbrace$

# Standard Output

One integer indicating the number of prime paths in the country.

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
1 2 1
2 3 1
2 4 1</td><td>3</td></tr><tr><td>5
1 2 1
2 3 0
3 4 1
4 5 1</td><td>4</td></tr></table>


# Constraints



# Note



# Source


