
# Content

Tom likes to travel and visit famous spots. One day he drives in a car to a strange country named BitLand and runs out of fuel, so he goes to a local gas station to fuel up his car. There are $N$ buckets of fuel on sale, each has a price and contains exactly $2^k$ liters of fuel, where k is specific to this bucket. In addition the worker at the station would only fuel up Tom's car if Tom buys exactly the amount of fuel equal to the volume of his car's tank.

Help Tom by giving him a fuel buying plan to minimize the amount of money he would spend.

# Standard Input

On the first line of the input is two integers $N$ and $M$, number of buckets of fuel on sold, and the volume of Tom's tank in liters. Next $N$ lines each contain two numbers $k$ and $p$, meaning this bucket contains exactly $2^k$ liters of fuel and costs $p$ dollars.

$0 \leq k \leq 30, 1 \leq N \leq 100000, 1 \leq M \leq 2000000000$
Prices are integers between $1$ and $1000$, inclusive.Output Output on a single line the minimum cost in dollars to buy exactly $M$ liters of fuel. If Tom can't fulfill the worker's requirement, output `-1` instead.

* $2^k$ means $2$ to the power of k, i.e. $2^0=1$, $2^1=2$, $2^2=4$, $2^3=8$, etc.

* The volume of Tom's tank can be very huge since 

# Standard Output

Output on a single line the minimum cost in dollars to buy exactly $M$ liters of fuel. If Tom can't fulfill the worker's requirement, output `-1` instead.

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
<tr><td>3 5
0 1
1 2
2 3</td><td>4</td></tr></table>


# Constraints



# Note

There are $3$ buckets of fuel and Tom must buy exactly $5$ liters of fuel. The first bucket contains $1$ liter of fuel and costs $1$ dollar. The second contains $2$ liters and costs $2$ dollars. The third contains $4$ liters and costs $3$ dollars. Tom can buy the first bucket and the third, for a total cost of $4$ dollars.

# Source


