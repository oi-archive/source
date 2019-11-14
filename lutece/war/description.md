
# Content

Your country is now involved in a war! In the front, there are $N$ positions between which you can transfer goods. Unfortunately the enemies will attack you and destroy some positions. When transferring, you cannot pass through a position which has been destroyed. As the commander of the army, you want to know the minimum distance between some position $u$ and $v$, after some positions have been destroyed.

# Standard Input

The first line of inputs gives $t (t \leq 15)$ indicating the number of test cases.
Then $t$ blocks follow. The first line of each block gives $n$ and $m (2 \leq n \leq 200, 0 \leq m \leq 100000)$ indicating the number of positions and number of roads. Each of the next $m$ lines contains $3$ integers $u, v$ and $e (1 \leq u, v \leq n, 1 \leq e \leq 1000)$, telling that there is a road between position $u$ and position $v$ and the distance of the road is $e$. An integer $q (q \leq 10000)$ follows in the next line representing the number of queries to process. Each of the next $q$ lines has one of the following formats:

A.	$0$ $u$ $v$: This means you should reply with the shortest path between position $u$ and position $v$.

B.	$1$ $u$: This means position $u$ is destroyed.

You should notice that all the positions are not destroyed initially and there could be more than one road between two positions.

# Standard Output

For all the queries in the format $A:0$ $u$ $v$, if any of the queried position is destroyed or there is no path from $u$ to $v$, print `-1`; otherwise print the shortest path between the two positions. Print a blank line after each test case.

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
4 4
1 2 1
1 3 3
2 4 2
3 4 4
5
0 1 4
1 2
0 1 4
1 3
0 1 4</td><td>3
7
-1</td></tr></table>


# Constraints



# Note



# Source


