
# Content

Tree land has $n$ cities, connected by $n-1$ roads. You can go to any city from any city. In other words, this land is a tree. The city numbered one is the root of this tree.

There are $n$ ministers numbered from $1$ to $n$. You will send them to $n$ cities, one city with one minister. 

Since this is a rooted tree, each city is a root of a subtree and there are $n$ subtrees. The leader of a subtree is the minister with maximal number in this subtree. As you can see, one minister can be the leader of several subtrees. 

One day all the leaders attend a meet, you find that there are exactly $k$ ministers. You want to know how many ways to send $n$ ministers to each city so that there are $ k$ ministers attend the meet.

Give your answer mod $1000000007$.

# Standard Input

Multiple test cases. In the first line there is an integer $T$, indicating the number of test cases. For each test case, first line contains two numbers $n, k$. Next $n-1$ line describe the roads of tree land.

$T=10,1\leq n\leq 1000,1\leq k\leq n$

# Standard Output

For each test case, output one line. The output format is Case #$x$: $ans$, $x$ is the case number,starting from $1$.

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
3 2
1 2
1 3
10 8
2 1
3 2
4 1
5 3
6 1
7 3
8 7
9 7
10 6
</td><td>Case #1: 4
Case #2: 316512

</td></tr></table>


# Constraints



# Note



# Source


