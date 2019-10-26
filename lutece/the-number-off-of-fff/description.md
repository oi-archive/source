
# Content

$X$ soldiers from the famous "**`FFF`** army'' is standing in a line, from left to right.

You, as the captain of **`FFF`**, decides to have a `number off`, that is, each soldier, 
from left to right, calls out a number. 
The first soldier should call `One`, each other soldier should call the number next to the number 
called out by the soldier on his left side. If every soldier has done it right, 
they will call out the numbers from $1$ to $X$, one by one, from left to right.

Now we have a continuous part from the original line.
There are $N$ soldiers in the part. 
So in another word, we have the soldiers whose id are between $A$ and $A + N - 1$ ($1 \leq A \leq A + N - 1 \leq X$).
However, we don't know the exactly value of $A$, but we are sure the soldiers stands continuously in the original line, from left to right.

We are sure among those $N$ soldiers, exactly one soldier has made a mistake. 
Your task is to find that soldier.

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

For each test case there are two lines. First line has the number $N$, 
and the second line has $N$ numbers, as described above. ($3\leq N \leq 10^5$)

It guaranteed that there is exactly one soldier who has made the mistake.

# Standard Output

For test case $X$, output in the form of `Case #X: L`, $L$ here means the position of soldier among the $N$ soldiers 
counted from left to right based on $1$.

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
3
1 2 4
3
1001 1002 1004</td><td>Case #1: 3
Case #2: 3</td></tr></table>


# Constraints



# Note



# Source


