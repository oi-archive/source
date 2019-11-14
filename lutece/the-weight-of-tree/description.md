
# Content

456 has a tree of $n$ nodes, each node is assigned with an integer number. Now 456 wants to select a subtree, such that the sum of all integers on the nodes of the subtree is maxmized.

Can you help him?

# Standard Input

On the first line of the input is an integer $T$, and then $T$ cases follows. Each case begins with a positive integer $n$($1\leq n\leq 10^5$), then $n$ numbers $W\_i$($-1000\leq W\_i\leq 1000$),$W\_i$ for the number on the $i\_{th}$ node. Then $n - 1$ lines follows, each line contains two numbers $a$, $b$($1\leq a, b\leq n$) indicate that there is a edge between node $a$ and $b$.

# Standard Output

For each test case, output one integer on a line, the maximized sum can be achieved by selecting a subtree.

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
1
5
2
5 -5
1 2
5
-2 -3 7 -1 4
1 2
2 3
3 4
2 5</td><td>5
5
8</td></tr></table>


# Constraints



# Note



# Source


