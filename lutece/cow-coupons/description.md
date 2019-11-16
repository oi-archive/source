
# Content

Farmer John needs new cows! There are $N$ cows for sale ($1 \leq N \leq 50,000$), and FJ has to spend no more than his budget of $M$ units of money ($1 \leq M \leq 10^{14}$). Cow $i$ costs $P\_i$ money ($1 \leq P\_i \leq 10^9$), but FJ has $K$ coupons ($1 \leq K \leq N$), and when he uses a coupon on cow $i$, the cow costs $C\_i$ instead ($1 \leq C\_i \leq P\_i$). FJ can only use one coupon per cow, of course.

# Standard Input

* Line $1$: Three space-separated integers: $N$, $K$, and $M$.
* Lines $2\cdots N+1$: Line $i+1$ contains two integers: $P\_i$ and $C\_i$.

# Standard Output

* Line $1$: A single integer, the maximum number of cows FJ can afford.

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
<tr><td>4 1 7
3 2
2 2
8 1
4 3</td><td>3</td></tr></table>


# Constraints



# Note

FJ uses the coupon on cow $3$ and buys cows $1$, $2$, and $3$, for a total cost of
$3 + 2 + 1 = 6$.

# Source


