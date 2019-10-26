
# Content

Chiara has $N$ cups, numbered from $1$ to $N$. Cups are laid on a table, each upward or downward. Chiara enjoys turning cups. Every time she will select $M$ cups and play her silly game. If a cup is upward, it will be downward after her turning, and vice versa. One day, Chiara's $N$ friends are coming to see her. She'd like to use the $N$ cups for coffee serving (Chiara is addicted to coffee desperately, that's...OK). However, the cups are not all upward. She is wondering if it is possible to make them all upward after several turnings. Since time is limited, you have to give her the minimum number of steps. 

Note: Chiara has to turn $M$ cups each time.

# Standard Input

There are multiple cases. The first line is an integer $T(1 \leq T \leq 20)$, then following $T$ cases.

For each case:

The first line has two integers $N(1 \leq N \leq 10000)$，$M(1 \leq M \leq 10, M \leq N)$. $N$ is the total number of cups and $M$ is the number of cups Chiara has to turn each time.

The second line has $N$ numbers, either $0$ or $1$($0$ for upward and $1$ for downward), separated by spaces.

# Standard Output

If Chiara can achieve her goal, please output the minimum number of turnings, otherwise print `Poor Girl`.

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
6
3
0 0 0 1 1 1
2
2
0 1</td><td>1
Poor Girl</td></tr></table>


# Constraints



# Note



# Source


