
# Content

There are many trees in the grove.We can assume that grove is a $m \times n$ grid, the grid starts from $(1,1)$. Farmer Sherlock is standing at $(0,0)$ point. He wonders how many trees he can see.

If two trees and Sherlock are in one line, Farmer Sherlock can only see the tree nearest to him.

# Standard Input

The first line contains one integer $t$, represents the number of test cases. Then there are multiple test cases. For each test case there is one line containing two integers m and $n(1 \leq m, n \leq 100000)$

# Standard Output

For each test case output one line represents the number of trees Farmer Sherlock can see.

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
1 1
2 3</td><td>1
5</td></tr></table>


# Constraints



# Note

In case $2$, trees in $(1,1) (1,2) (1,3) (2,1) (2,3)$ are visible. But tree in $(2,2)$ is invisible. The answer may exceed $32$-bit integer. Please use long long int.
The data used in this problem is unofficial data prepared by RedWall. So any mistake here does not imply mistake in the offcial judge data.

# Source


