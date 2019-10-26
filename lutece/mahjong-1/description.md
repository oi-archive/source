
# Content

The game of Mahjong originated in China and has become popular around the world. You do not need to have prior experience with Mahjong to solve this problem, and we will use different rules.

In our version of Mahjong, the player is given a set of $4K$ tiles. Each tile has an integer rank written on it, and there are four identical copies of each rank from $1$ to $K$.
For example, for $K = 5$, the set of tiles would be: `1`, `1`, `1`, `1`, `2`, `2`, `2`, `2`, `3`, `3`, `3`, `3`, `4`, `4`, `4`, `4`, `5`, `5`,
`5`, `5`.

The player's goal is to select $M$ tiles from this set to form a winning hand. A *winning* hand consists of some number (possibly zero) of *triples* plus **exactly** one pair.
A pair must consist of two tiles of the same rank. A triple can be either three tiles of the same rank (e.g., `2 2 2`), or three tiles with consecutive ranks
(e.g., `3 4 5`). The ranks do not wrap around -- for example, `4 5 1` is not a valid triple.

Given $K$ and $M$, how many different winning hands are there? Two winning hands are considered the same if they use the same set of tiles, regardless of how those tiles are grouped to
make triples and the pair. For instance, for $K = 4$, $M = 8$, the following two hands are considered the same:

`1 2 3, 1 2 3, 4 4`

`1 1, 2 3 4, 2 3 4`

# Standard Input

The first line of the input gives the number of test cases, $T$($1\leq T\leq 100$). $T$ lines follow. Each line contains two space-separated integers, $K$($1\leq K\leq 200$)
and $M$($2\leq M\leq min(200, 4K)$ and $M \equiv 2 \pmod{3}$).

# Standard Output

For each test case, output one line containing `Case #x: y`, where $x$ is the test case number (starting from $1$) and $y$ is the number of winning hands,
modulo $1000000007$ ($10^9 + 7$).

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
1 2
3 5
4 5
9 14</td><td>Case #1: 1
Case #2: 9
Case #3: 20
Case #4: 13259</td></tr></table>


# Constraints



# Note

In `Case #1`, there are only four tiles -- `1`, `1`, `1`, `1` -- and the winning hand must consist of just a pair (with no triples).
There is only one possibility -- `1 1`. (Note that all the `1`s are interchangeable and it doesn't matter which two you pick.)

In `Case #2`, there are twelve tiles -- `1`, `1`, `1`, `1`, `2`, `2`, `2`, `2`, `3`, `3`, `3`, `3` -- and the winning hand must consist of one triple and one pair.
The nine possible hands are:

```
1 1 1, 2 2
1 1 1, 3 3
2 2 2, 1 1
2 2 2, 3 3
3 3 3, 1 1
3 3 3, 2 2
1 2 3, 1 1
1 2 3, 2 2
1 2 3, 3 3
```

Note that `3 3, 1 1 1` would not be considered a different hand from `1 1 1, 3 3` -- only the set of tiles matters, not how they are arranged.

# Source


