
# Content

Lillian gets some segments from her fans with lengths of 1,2,3... and she intends to add them to a number line.At the i-th add operation,she will put the segment with length of i on the number line.Every time she put the segment on the line,she will count how many entire segments on that segment.During the operation ,she may delete some segments on the line.

(Segments are mutually independent)

# Standard Input

There are multiple test cases.

The first line of the input contains a integer n — the number of operations($1<=n<=2 \times 10^5$)

Next n lines contain the descriptions of the operatons,one operation per line.Each operation contains two integers $a$, $b$. 

if $a$ is $0$, it means add operation that Lilian put a segment on the position b($|b|<10^9$) of the line.
(For the i-th add operation,she will put the segment on [b,b+i] of the line, with length of $i$.)

if $a$ is $1$, it means delete operation that Lilian will delete the segment which was added at the b-th add operation.

# Standard Output

For i-th case,the first line output the test case number.

Then for each add operation,ouput how many entire segments on the segment which Lillian newly adds.

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
<tr><td>3
0 0
0 3
0 1
5
0 1
0 0
1 1
0 1
0 0</td><td>Case #1:
0
0
0
Case #2:
0
1
0
2</td></tr></table>


# Constraints



# Note

At the first add operation,Lillian adds a segment [1,2] on the line.

At the second add operation,Lillian adds a segment [0,2] on the line.

At the delete operation,Lillian deletes a segment which added at the first add operation.

At the third add operation,Lillian adds a segment [1,4] on the line.

At the fourth add operation,Lillian adds a segment [0,4] on the line.

# Source


