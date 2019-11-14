
# Content

Since milk packaging is such a low margin business, it is important to keep the price of the raw product (milk) as low as possible. Help Merry Milk Makers get the milk they need in the cheapest possible manner.

The Merry Milk Makers company has several farmers from which they may buy milk, and each one has a (potentially) different price at which they sell to the milk packing plant. Moreover, as a cow can only produce so much milk a day, the farmers only have so much milk to sell per day. Each day, Merry Milk Makers can purchase an integral amount of milk from each farmer, less than or equal to the farmer's limit.

Given the Merry Milk Makers' daily requirement of milk, along with the cost per gallon and amount of available milk for each farmer, calculate the minimum amount of money that it takes to fulfill the Merry Milk Makers' requirements.

Note: The total milk produced per day by the farmers will be sufficient to meet the demands of the Merry Milk Makers.

# Standard Input

Line $1$: Two integers, $N$ and $M$.

The first value, $N$, ($0\leq N\leq 2,000,000$) is the amount of milk that Merry Milk Makers' want per day. The second, $M$, ($0\leq M\leq 5,000$) is the number of farmers that they may buy from.

Lines $2$ through $M+1$: The next $M$ lines each contain two integers, $P\_i$ and $A\_i$.

$P\_i$ ($0\leq P\_i\leq 1,000$) is price in cents that farmer $i$ charges.

$A\_i$ ($0\leq A\_i\leq 2,000,000$) is the amount of milk that farmer $i$ can sell to Merry Milk Makers per day.

# Standard Output

A single line with a single integer that is the minimum price that Merry Milk Makers can get their milk at for one day.

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
<tr><td>100 5
5 20
9 40
3 10
8 80
6 30</td><td>630</td></tr></table>


# Constraints



# Note



# Source


