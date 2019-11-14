
# Content

The winter is coming and all the experts are warning that it will be the coldest one in the last hundred years. Freddy needs to make sure that his garden does not sustain any damage. One of the most important tasks is to make sure that no water remains in his large watering system.

All the water comes from a central node and is distributed by pipes to neighboring nodes and soon. Each node is either a sprinkler (rose head) with no outgoing pipe or an internal node with one or more outgoing pipes leading to some other nodes. Every node has exactly one incoming pipe, except for the central node which takes the water directly from a well and has no incoming pipe. Every pipe has a valve that stops all the water going through the pipe. The valves are of different quality and age, so some may be harder to close than others.

Freddy knows his valves well and has assigned a value to each pipe representing the amount of effort needed to close the corresponding valve. He asks you to help him count the minimum effort needed to close some valves so that no water goes to the sprinklers.

# Standard Input

The input contains several test cases. Each test case starts with a line with two integers, the number of nodes $n$ ($2\leq n\leq 1,000$), and the number of the central node $c$ ($1\leq c\leq n$). Each of the next $n - 1$ lines represents one pipe and contains three integers, $u$, $v$ ($1\leq u, v\leq n$) and $w$($1\leq w\leq 1,000$), where $u$ and $v$ are the nodes connected by a pipe and $w$ is the effort needed to close the valve on that pipe. You may assume that every node is reachable from the central node.

# Standard Output

For each test case, output a single line containing the minimum sum of efforts of valves to be closed, such that the central node gets separated from all sprinklers.

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
<tr><td>3 1
2 1 5
1 3 4
7 7
7 6 10
7 5 10
6 4 1
6 3 1
5 2 1
5 1 2</td><td>9
5</td></tr></table>


# Constraints



# Note

Adapted from Stanford Local ACM Contest 2009

# Source


