
# Content

For many sets of consecutive integers from $1$ through $N$ ($1\leq N\leq 39$), one can partition the set into two sets whose sums are identical.

For example, if $N=3$, one can partition the set $\\{1, 2, 3\\}$ in one way so that the sums of both subsets are identical:

* $\\{3\\}$ and $\\{1,2\\}$ 

This counts as a single partitioning (i.e., reversing the order counts as the same partitioning and thus does not increase the count of partitions).

If $N=7$, there are four ways to partition the set $\\{1, 2, 3, \cdots 7\\}$ so that each partition has the same sum:

* $\\{1,6,7\\}$ and $\\{2,3,4,5\\}$
* $\\{2,5,7\\}$ and $\\{1,3,4,6\\}$
* $\\{3,4,7\\}$ and $\\{1,2,5,6\\}$
* $\\{1,2,4,7\\}$ and $\\{3,5,6\\}$ 

Given $N$, your program should print the number of ways a set containing the integers from $1$ through $N$ can be partitioned into two sets whose sums are identical. Print $0$ if there are no such ways.

Your program must calculate the answer, not look it up from a table.

# Standard Input

The input file contains a single line with a single integer representing $N$, as above.

# Standard Output

The output file contains a single line with a single integer that tells how many same-sum partitions can be made from the set $\\{1, 2, \cdots N\\}$. The output file should contain $0$ if there are no ways to make a same-sum partition.

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
<tr><td>7</td><td>4</td></tr></table>


# Constraints



# Note



# Source


