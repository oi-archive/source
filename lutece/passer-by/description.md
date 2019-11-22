
# Content

There are n cities ,which are labeled from $0$ to $N-1$, and a passer-by wants to go to city $N-1$ from city $0$.There may be a directed road between two cities,or there is not any road between them.

However, because of the `National Environmental Action`,some of the roads have to be closed and nobody is allowed to use it until it is cleaned up.The passer-by wants to achieve at city $n-1$ as soon as possible,so please help him calculate the shortest time he need to reach the destination.

# Standard Input

There are several test cases, first line is an integer $T(1 \leq T \leq 10)$, represents there are $T$ test cases.

The first line of each test are two integers: $N$ and $M$, which respectively represent the number of cities and the number of roads. $(N \leq 1000, M \leq 1000000)$

Each of the following m lines includes four integers: $U, V, W, T$.Which means that there exists a one-way road from $U$ to $V$ and crossing it will cost $W$ minutes.In addition, the road will not be available until $T$ minutes when the road is cleaned up. There is at most one road from $U$ to $V (0 \leq U < N), (0 \leq V < N), (1 \leq W \leq 1000), (0 \leq T \leq 1000)$

# Standard Output

If the passer-by could get to the city $N-1$,then print the shortest time;

else if he couldn't ,then print `-1`.

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

3 3
0 1 2 0
0 2 8 0
1 2 3 6

3 3
0 1 2 0
0 2 8 0
1 2 3 4</td><td>8
7</td></tr></table>


# Constraints



# Note

Huge input, scanf recommend

# Source


