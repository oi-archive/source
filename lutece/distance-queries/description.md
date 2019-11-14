
# Content

Farmer John's cows refused to run in his marathon since he chose a path much too long for their leisurely lifestyle. He therefore wants to find a path of a more reasonable length. The input to this problem consists of the same input as in `Navigation Nightmare`,followed by a line containing a single integer $K$, followed by $K$ `distance queries`. Each distance query is a line of input containing two integers, giving the numbers of two farms between which FJ is interested in computing distance (measured in the length of the roads along the path between the two farms). Please answer FJ's distance queries as quickly as possible!

# Standard Input

* Line $1$: Two space-separated integers: $N$ and $M$

* Lines $2 \cdots M+1$: Each line contains four space-separated entities, $F1,F2, L,$ and $D$ that describe a road. $F1$ and $F2$ are numbers of
two farms connected by a road, $L$ is its length, and $D$ is a
character that is either `N`, `E`, `S`, or `W` giving the
direction of the road from $F1$ to $F24.

* Line $2+M$: A single integer, $K. 1 \leq K \leq 10,000$

* Lines $3+M \leq 2+M+K$: Each line corresponds to a distance query and contains the indices of two farms.

# Standard Output

Lines $1 \cdots K$: For each distance query, output on a single line an integer giving the appropriate distance.

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
<tr><td>7 6
1 6 13 E
6 3 9 E
3 5 7 S
4 1 3 N
2 4 20 W
4 7 2 S
3
1 6
1 4
2 6</td><td>13
3
36</td></tr></table>


# Constraints



# Note

Farms $2$ and $6$ are $20+3+13=36$ apart.

# Source


