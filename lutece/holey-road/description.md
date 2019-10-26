
# Content

You are manouvering a tiny remote-controlled car along a road in very bad condition; the road is full of holes. The car is unable to drive over the holes, since it would plunge into the hole and become damaged beyond repair. In addition, driving off the road will cause the car to be forever lost in the tall grass surrounding it.

The car is so small that it can be considered as a point with no spatial extension. The road is $W$ meters wide and $L$ meters long, and it runs parallel to the $y$-axis. Your car starts at $(\frac{W}{2},0)$ and your destination is $(\frac{W}{2},L)$.All of the holes happen to be perfectly circle-shaped, and none of them intersect or touch other holes or the edges of the road.

You want to take the shortest possible path to the destination. Write a program that calculates the length of such a path.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each test case begins with a line containing three integers $N,W,L$, the number of holes, and the width and the length of the road, respectively. Then follow $N$ lines each containing three integers $x\_i,y\_i,r\_i$ representing a hole with center $x\_i,y\_i$ and radius $r\_i$.

# Standard Output

For each test case, output the length of the shortest possible path from the starting position to the final position that avoids holes. An error of up to $10^{-6}$ will be accepted in the output.

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
1 50 1000
20 500 5
1 50 1000
25 500 5
3 100 1000
50 50 25
25 150 24
75 150 24</td><td>1000.00000000000
1000.05000041668
1009.34797846036</td></tr></table>


# Constraints



# Note

$0 < T \leq 100$

$0 \leq N \leq 100$

$0 < L \leq 1000$

$0 < W \leq 100$

$r\_i < x\_i < W - r\_i$

$r\_i < y\_i < L - r\_i$

$0 < r\_i < min(\left \lfloor \frac{W}{2} \right \rfloor, \left \lfloor \frac{L}{2} \right \rfloor)$

# Source


