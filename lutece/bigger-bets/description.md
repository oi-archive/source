
# Content

In some country live wizards. They like to make weird bets.

Two wizards draw $k$ points on the left named sources and draw $k$ points on the right named sinks.Wizards numbered the sources in the order of increasing numbers of the vertices from $1$ to $k$. The sinks are numbered from $1$ to $k$ in the similar way.And in the magic world,the sources $i$ to sink $j$ would have $gcd(i,j)^t$ paths.

To make a bet, they, as are real wizards, cast a spell, which selects a set of $k$ paths from all sources to the sinks in such a way . In this case, each sink has exactly one path going to it from exactly one source. Let's suppose that the $i$-th sink has a path going to it from the $ai$'s source. Then let's call pair (i, j) an inversion if $i < j$ and $a_i > a_j$. If the number of inversions among all possible pairs (i, j), such that $(1 ≤ i < j ≤ k)$, is even, then the first wizard wins (the second one gives him one magic coin). Otherwise, the second wizard wins (he gets one magic coin from the first one).

Our wizards are captured with feverish excitement, so they kept choosing new paths again and again for so long that eventually they have chosen every possible set of paths for exactly once. The two sets of non-intersecting pathes are considered to be different, if and only if there is an edge, which lies at some path in one set and doesn't lie at any path of another set. To check their notes, they asked you to count the total winnings of the first player for all possible sets of paths modulo a prime number $1000000007$.

# Standard Input

First line of input consists of a single integer containing the number of test cases $T$( equal to around 50)

each of the following $T$ lines contain two integer $k,t$. $k$ lies between $1$ and $1000000$, $t$ lies between $1$ and $1000000$

# Standard Output

For each test case, print a single line contains the answer.

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
1 1
2 2
3 3</td><td>1
3
182</td></tr></table>


# Constraints



# Note



# Source


