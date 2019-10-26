
# Content

For a sequence $S\_1,S\_2,\cdots ,S\_N$, and a pair of integers ($i$, $j$), if $1 \leq i \leq j \leq N$ and $S\_i < S\_{i+1} < S\_{i+2} <\cdots < S\_{j-1} < S\_j$, then the sequence $S\_i,S\_{i+1},\cdots ,S\_j$ is a `CIS` (Continuous Increasing Subsequence). The longest `CIS` of a sequence is called the `LCIS` (Longest Continuous Increasing Subsequence).

Now we consider a tree rooted at node $1$. Nodes have values. We have $Q$ queries, each with two nodes $u$ and $v$. You have to find the shortest path from $u$ to $v$. And write down each nodes' value on the path, from $u$ to $v$, inclusive. Then you will get a sequence, and please show us the length of its `LCIS`.

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

For each test case, the first line is a number $N$ ($N \leq 10^5$), the number of nodes in the tree.

The second line comes with $N$ numbers $v\_1,v\_2,v\_3\cdots ,v\_N$, describing the value of node $1$ to node $N$.  ($1 \leq v\_i \leq 10^9$)

The third line comes with $N-1$ numbers $p\_2,p\_3,p\_4\cdots ,p\_N$, describing the father nodes of node $2$ to node $N$. Node $1$ is the root and will have no father.

Then comes a number $Q$, it is the number of queries. ($Q \leq 10^5$)

For next $Q$ lines, each with two numbers $u$ and $v$. As described above.

# Standard Output

For test case $X$, output `Case #X: ` at the first line.

Then output $Q$ lines, each with an answer to the query.

There should be a blank line **`BETWEEN`** each test case.

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
<tr><td>1
5
1 2 3 4 5
1 1 3 3
3
1 5
4 5
2 5</td><td>Case #1:
3
2
3</td></tr></table>


# Constraints



# Note



# Source


