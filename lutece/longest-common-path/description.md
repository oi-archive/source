
# Content

Per and Pal are friends, and like to hang out together. They are also very impatient, so they always take the shortest possible way when they need to go somewhere.

It's the end of the school day, and they need to go home.Naturally, they want to arrive at home as early as possible. They also want to maximize the time they walk together while walking towards their homes. You have been asked to write a computer program that calculates the maximal time they can walk together. Their neighbourhood is modelled as a graph where intersections are nodes and roads are edges.The roads are bidirectional, and it takes the same time to traverse a road in both directions. All important destinations happen to be located at an intersection. Also,the school and the two homes are never located at the same intersection. There exists a path between every pair of intersections.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. The next line contains two integers $N$ and $M$, the number of intersections and the number of bidirectional roads in the city, respectively. The following line contains three integers $S,P$ and $Q$, indicating the position of the school, Per's home and Pal's home, respectively. The next $M$ lines contain three integers $a\_i,b\_i$ and $c\_i$, indicating that there is a bidirectional road between intersections $a\_i$ and $b\_i$ which takes $c\_i$ minutes to traverse. All intersections are numbered from $0$ to $N-1$, inclusive.

# Standard Output

For each test case, output the length of the longest distance Per and Pal can walk together while still arriving at their own homes as fast as possible.

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
4 5
0 2 3
0 1 100
1 2 50
1 3 40
0 2 500
0 3 500
4 5
0 2 3
0 1 100
1 2 50
1 3 40
0 2 10
0 3 10</td><td>100
0</td></tr></table>


# Constraints



# Note

$0 < T \leq 100$

$3 \leq N \leq 2000$

$N-1 \leq M \leq min(\frac{N\times (N-1)}{2},10000)$

$0 \leq a\_i < b\_i < N$

$0 < c\_i \leq 1000$

$0 \leq S,P,Q,a\_i,b\_i < N$

# Source


