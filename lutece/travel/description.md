
# Content

Given a map of islands and bridges that connect these islands, a Hamilton path, as we all know, is a path along the bridges such that it visits each island exactly once.

Suppose there are $n$ islands and $m$ bridges. Now we want to know there are how many different Hamilton paths?

# Standard Input

The input file starts with a number $C$ (no more than $100$) on the first line, which is the number of test cases. Each test case starts with a line with two integers n and m, which are the number of islands and the number of bridges in the map, respectively. The following m lines are in the form $x$ $y$, which indicates there is a (two way) bridge between island $x$ and island $y$. Islands are numbered from $1$ to $n$. You may assume there will be no more than $15$ islands. (The data are generated randomly,so $n=15$ only in a few cases)

# Standard Output

For each test case, output a line with a number represent the number of different Hamilton paths.

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
2 1
1 2
4 4
1 2
1 3
2 3
3 4</td><td>2
4</td></tr></table>


# Constraints



# Note

case $1$:$1->2$ and $2->1$

case $2$:$1->2->3->4 , 2->1->3->4 , 4->3->1->2 , 4->3->2->1$

The answer may exceed $32$-bit integer. Please use long long int.

# Source


