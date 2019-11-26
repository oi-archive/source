
# Content

Gollum is finding his Precious. The precious is hiding in a magic maze. The maze can be considered as a simple polygon. Some vertexes of the polygon are doors that can only allow Gollum to get in, and the other doors can only allow Gollum to get out. 

Gollum doesn't know that restrict, he choose a door to get in, and choose a door to get out after he has got his precious. Gollum hasn't learned math, so we believe that Gollum choose the door randomly, that means if there are $n$ doors, the probability of a door chose by Gollum is $\frac{1}{n}$. 

There is a monster in the maze, and if Gollum stay in the maze more than m minutes, the monster will wake up and eat Gollum. Gollum can move one unit distance by one minute. 

We want to know the probability that Gollum got his precious.

# Standard Input

The input consists of multiply test cases. The first line of each test case contains two integers, $n$ ($3\leq n\leq 100$), $m$ ($0\leq m\leq 10000$), where $n$ is the number of vertexes of the maze, and $m$ is the time limit. 

The next $n$ lines represent the maze, each line contains a coordinate, $x$, $y$ ($-10000\leq x, y\leq 10000$) and a DoorType. 

If DoorType equals to $-1$, then you can get in from this vertex; 

if DoorType equals to $0$, then it's not a door; 

if DoorType equals to $1$, then you can get out from this vertex. The last line of each test case is a coordinate, indicating the location of the precious. You can assume that the precious is always in the maze. 

The last test case is followed by a line containing two zeros, which means the end of the input.

# Standard Output

Output the probability. Please take it with $9$ factional digits

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
<tr><td>12 4 
-2 -1 -1 
-1 -1 -1 
-1 -2 -1 
1 -2 -1 
1 -1 -1 
2 -1 -1 
2 1 1 
1 1 1 
1 2 1 
-1 2 1 
-1 1 1 
-2 1 1 
0 0 
0 0</td><td>0.138888889</td></tr></table>


# Constraints



# Note



# Source


