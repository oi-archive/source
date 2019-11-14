
# Content

You and your friend are playing a game in which you and your friend take turns removing stones from piles. Initially there are $N$ piles with $a\_{1}, a\_{2}, a\_{3}, …, a\_{N}$ number of stones. On each turn, a player must remove at least one stone from one pile but no more than half of the number of stones in that pile. The player who cannot make any moves is considered lost. For example, if there are three piles with $5$, $1$ and $2$ stones, then the player can take $1$ or $2$ stones from first pile, no stone from second pile, and only $1$ stone from third pile. Note that the player cannot take any stones from the second pile as $1$ is more than half of $1$ (the size of that pile). Assume that you and your friend play optimally and you play first, determine whether you have a winning move. You are said to have a winning move if after making that move, you can eventually win no matter what your friend does.

# Standard Input

The first line of input contains an integer $T$ $(T ≤ 100)$ denoting the number of testcases. Each testcase begins with an integer $N$ $(1 ≤ N ≤ 100)$ the number of piles. The next line contains $N$ integers $a\_{1}, a\_{2}, a\_{3}, …, a\_{N}$ $(1 ≤ a\_{i} ≤ 2 * 10^{18})$ the number of stones in each pile.

# Standard Output

For each testcase, print “$YES$” (without quote) if you have a winning move, or “$NO$” (without quote) if you don‟t have a winning move.

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
2
4 4
3
1 2 3
3
2 4 6
3
1 2 1</td><td>NO
YES
NO
YES</td></tr></table>


# Constraints



# Note



# Source


