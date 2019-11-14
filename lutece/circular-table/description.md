
# Content

There are $n$ people sit around a circular table with $n$ seats.

It's obvious that there will be $n!$ ways to arrange their position, but the arrangement does not go well, because there are some pairs of people who are unwilling to sit with the another.

More precisely, the people numbered from $1$ to $n$, and the relation of them can be described as $m$ unordered pairs $\{u,v\}$, meaning that the people numbered $u$ and the people numbered $v$ will not sit in two adjacent positions.

The meaning of adjacent positions is, if we number seats from $1$ to $n$ clockwise, the seat number $i$ is adjacent to the seat number $i+1$ for all $1\leq i\leq n-1$, in addition, the seat number $n$ is adjacent to the seat number $1$.

How many ways to arrange their position while nobody is unwilling?

# Standard Input

The first line contains two integers $n$ and $m$.

Then $m$ lines follow, each with two integers $u$ and $v$. ($u\neq v$)

It is guaranteed that every relation is mentioned no more than once.

$3\leq n\leq 10^6$

$0\leq m\leq 18$

$1\leq u, v \leq n$

# Standard Output

Print the number of ways to arrange their position while nobody is unwilling. As the answer may be too large, output it modulo $(10^9+7)$ (i.e. if the answer is $X$, you should output $X\ \%\ (10^9+7)$).

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
<tr><td>4 0</td><td>24</td></tr><tr><td>4 1
1 2</td><td>8</td></tr></table>


# Constraints



# Note



# Source


