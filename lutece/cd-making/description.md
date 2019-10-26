
# Content

Tom has $N$ songs and he would like to record them into CDs. A single CD can contain at most $K$ songs. In addition, Tom is very superstitious and he believes the number `13` would bring bad luck, so he will never let a CD contain exactly $13$ songs. Tom wants to use as few CDs as possible to record all these songs. Please help him.

# Standard Input

There are $T$ test cases. The first line gives $T$, number of test cases. $T$ lines follow, each contains $N$ and $K$, number of songs Tom wants to record into CDs, and the maximum number of songs a single CD can contain.

$1 \leq N \leq 1000, 1 \leq K \leq 1000$

# Standard Output

For each test case, output the minimum number of CDs required, if the above constraints are satisfied.

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
5 2
13 13</td><td>3
2</td></tr></table>


# Constraints



# Note

If Tom has $5$ songs to record and a single CD can contain up to $2$ songs, Tom has to use $3$ CDs at minimum, each contains $2$, $2$, $1$ songs, respectively.

In the second case, Tom wants to record $13$ songs, and a single CD can hold $13$ songs at most. He would have been able to use only $1$ CD if he were not so superstitious. However, since he will not record exactly $13$ songs into a single CD, he has to use $2$ CDs at least, the first contains $12$ songs and the second contains one(Other solutions to achieve $2$ CDs are possible, such as ($11$, $2$), ($10$, $3$), etc.).

# Source


