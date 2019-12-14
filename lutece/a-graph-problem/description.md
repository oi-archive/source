
# Content

There is an old country with $n$ cities and $m$ undirected roads.

Now, $k$ people will choose two different cities and go between them. Besides, no one will choose the same two cities.

Given the graph and the whole plan of these $k$ people, delete as more edges as you can, without ruining anyone's plans.

You should output the number of edges you can delete.

# Standard Input

The first line contains three integers, $n (1 \le n \le 15)$ , $m (0 \le m \le n*(n-1)/2)$ , $k (0 \le k \le n*(n-1)/2)$

On the next $m$ lines , each line contains two integers $a$, $b$, denoting the $i^{th}$ edge.

On the next $k$ lines, each line contains two integers $a$, $b$, denoting the $i^{th}$ people’s plan.

# Standard Output

Output the answer in one line.

If it has no solution, output `-1`.

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
<tr><td>4 6 6
1 2
1 3
1 4
2 3
2 4
3 4
1 2
1 3
1 4
2 3
2 4
3 4
</td><td>3</td></tr></table>


# Constraints



# Note



# Source


