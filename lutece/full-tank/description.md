
# Content

After going through the receipts from your car trip through Europe this summer, you realised that the gas prices varied between the cities you visited. Maybe you could have saved some money if you were a bit more clever about where you filled your fuel?

To help other tourists (and save money yourself next time), you want to write a program for finding the cheapest way to travel between cities, filling your tank on the way. We assume that all cars use one unit of fuel per unit of distance, and start with an empty gas tank.

# Standard Input

The first line of input gives $1 \leq n \leq 1000$ and $0 \leq m \leq 10000$, the number of cities and roads. Then follows a line with n integers $1 \leq p\_i \leq 100$, where $p\_i$ is the fuel price in the $i$_th city. Then follow $m$ lines with three integers $0 \leq u, v < n$ and $1 \leq d \leq 100$, telling that there is a road between $u$ and $v$ with length $d$. Then comes a line with the number $1 \leq q \leq 100$, giving the number of queries, and $q$ lines with three integers $1 \leq c \leq 100, s$ and $e$, where $c$ is the fuel capacity of the vehicle, $s$ is the starting city, and $e$ is the goal.

# Standard Output

For each query, output the price of the cheapest trip from $s$ to $e$ using a car with the given capacity, or `impossible` if there is no way of getting from $s$ to $e$ with the given car.

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
<tr><td>5 5
10 10 20 12 13
0 1 9
0 2 8
1 2 1
1 3 11
2 3 7
2
10 0 3
20 1 4</td><td>170
impossible</td></tr></table>


# Constraints



# Note



# Source


