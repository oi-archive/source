
# Content

The cows are journeying north to Thunder Bay in Canada to gain cultural enrichment and enjoy a vacation on the sunny shores of Lake Superior. Bessie, ever the competent travel agent, has named the Bullmoose Hotel on famed Cumberland Street as their vacation residence. This immense hotel has $N$ ($1\leq N\leq 50,000$) rooms all located on the same side of an extremely long hallway (all the better to see the lake, of course).

The cows and other visitors arrive in groups of size $D\_i$ ($1\leq D\_i\leq N$) and approach the front desk to check in. Each group $i$ requests a set of $D\_i$ contiguous rooms from Canmuu, the moose staffing the counter. He assigns them some set of consecutive room numbers $r\cdots r+D\_i-1$ if they are available or, if no contiguous set of rooms is available, politely suggests alternate lodging. Canmuu always chooses the value of r to be the smallest possible.

Visitors also depart the hotel from groups of contiguous rooms. Checkout $i$ has the parameters $X\_i$ and $D\_i$ which specify the vacating of rooms $X\_i\cdots X\_i +D\_i-1$ ($1\leq X\_i\leq N-D\_i+1$). Some (or all) of those rooms might be empty before the checkout.

Your job is to assist Canmuu by processing $M$ ($1\leq M < 50,000$) checkin/checkout requests. The hotel is initially unoccupied.

# Standard Input

* Line $1$: Two space-separated integers: $N$ and $M$
* Lines $2\cdots M+1$: Line $i+1$ contains request expressed as one of two possible formats: 
   1. Two space separated integers representing a check-in request: $1$ and $D\_i$ 
   2. Three space-separated integers representing a check-out: $2$, $X\_i$, and $D\_i$

# Standard Output

For each check-in request, output a single line with a single integer $r$, the first room in the contiguous sequence of rooms to be occupied. If the request cannot be satisfied, output $0$.

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
<tr><td>10 6
1 3
1 3
1 3
1 3
2 5 5
1 6</td><td>1
4
7
0
5</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by standy. So any mistake here does not imply mistake in the offcial judge data.

# Source


