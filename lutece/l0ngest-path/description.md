
# Content

A Yggdrazil blooming on the cover of the poetry. We must solve the mystery to open it for the forbidden knowledge.

Each node in the Yggdrazil had a magic number $w_i$, and there are branches connected some pair of nodes.

After checking Yggdrazil, we find there is exactly one simple path between each pair of nodes.

If we can find a longest simple path in the Yggdrazil whose differ between the maximum magic number and the minimum magic number in the path is not greater than $D$, we can open the old poetry and master the forbidden knowledge.

The length of a path is the number of nodes on it.

# Standard Input

The first line contains two integers $n$ and $D$, which mean the number of nodes in Yggdrazil, and the maximum differ limit.

The second line contains $n$ integers $w_1, w_2, ..., w_n$, which mean the magic number of nodes $1$, $2$, ..., $n$.

For the next $n - 1$ lines, each line contains two integers $u$, $v$, mean there is a branch connected node $u$ and node $v$.

$1 \leq n \leq 100000$, $0 \leq D \leq 10^9$, $-10^9 \leq w_i \leq 10^9$.

# Standard Output

An integer denote the length of the longest path in Yggdrazil which can help us open the old poetry.

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
<tr><td>5 2
1 2 3 4 5
1 2
2 3
2 4
2 5</td><td>3</td></tr></table>


# Constraints



# Note

The longest path which satisfies the limit is $1-2-3$.

# Source


