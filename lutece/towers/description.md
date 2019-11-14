
# Content

The city of D consists of $n$ towers, built consecutively on a straight line. The height of the tower that goes $i\_{th}$ (from left to right) in the sequence equals $h\_i$. The city mayor decided to rebuild the city to make it beautiful. In a beautiful city all towers are are arranged in non-descending order of their height from left to right.

The rebuilding consists of performing several (perhaps zero) operations. An operation constitutes using a crane to take any tower and put it altogether on the top of some other neighboring tower. In other words, we can take the tower that stands $i\_{th}$ and put it on the top of either the $(i-1)\_{th}$ tower (if it exists), or the $(i+1)\_{th}$ tower (of it exists). The height of the resulting tower equals the sum of heights of the two towers that were put together. After that the two towers can't be split by any means, but more similar operations can be performed on the resulting tower. Note that after each operation the total number of towers on the straight line decreases by $1$.

Help the mayor determine the minimum number of operations required to make the city beautiful.

# Standard Input

The first line of each test case contains a single integer $n$ ($1\le n\le 5000$) — the number of towers in the city. The next line contains $n$ space-separated integers: the $i\_{th}$ number $h\_i$ ($1\le h\_i\le 10^5$) determines the height of the tower that is $i\_{th}$ (from left to right) in the initial tower sequence.

# Standard Output

For each test case,print a single integer — the minimum number of operations needed to make the city beautiful.

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
<tr><td>5
8 2 7 3 1
3
5 2 1</td><td>3
2</td></tr></table>


# Constraints



# Note



# Source


