
# Content

Saerdna likes travelling, but he can not afford the GPS. He only has a broken map with him. However, he could only find out the approximate locations of the tourist attractions with the map which is too dilapidated. After arriving there, he could ask for the specific destination. Can you help him?

# Standard Input

The first line of the input is an integer $T$($T\leq 10$), which represents that there are $T$ test cases.

Each test case starts with two integers $R$, $U$($U\leq 20$) representing the number of points and the number of connected blocks in the map. 

And then $U$ blocks follow. 

The first line of each block contains two integers $K$($K\leq 20$), $I$($I\leq K^2$), which represent the number of points and the number of edges in each connected block.

This is followed by $I$ lines, each line contains three integers $a$, $b$, $c$, which represents that there is an edge between $a$ and $b$ with the length $c$($c\leq 100000$).

After the $U$ blocks, there is an integer $Q$ ($Q\leq 5000$), for $Q$ queries.

Next there are $Q$ lines; each line has one of the two forms as follow:
* `add a b c`
* `query a b`

# Standard Output

Each case starts with `Case :S` ($S$ represents for the case number).

Then for each query, print the shortest path between $a$ and $b$, if there is no path, print $-1$.Print each answer in a line.

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
4 2
2 1
0 1 1
2 1
2 3 1
3
query 0 3
add 1 2 2
query 0 3</td><td>Case :1
-1
4</td></tr></table>


# Constraints



# Note

1. We guarantee that $a$ and $b$ are not in the same connected block when add edge.
2. Point numbers in the same connected block are continues.

# Source


