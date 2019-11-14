
# Content

Farmer John's pastoral neighborhood has $N$ farms $(2 \leq N \leq 40,000)$, usually numbered/labeled $1 \cdots N$. A series of $M (1 \leq M < 40,000)$ vertical and horizontal roads each of varying lengths $(1 \leq length \leq 1000)$ connect the farms. A map of these farms might look something like the illustration below in which farms are labeled $F1 \cdots F7$ for clarity and lengths between connected farms are shown as $(n)$:
```
           F1 --- (13) ---- F6 --- (9) ----- F3
            |                                 |
           (3)                                |
            |                                (7)
           F4 --- (20) -------- F2            |
            |                                 |
           (2)                               F5
            | 
           F7 
```
Being an ASCII diagram, it is not precisely to scale, of course.

Each farm can connect directly to at most four other farms via roads that lead exactly north, south, east, and/or west. Moreover, farms are only located at the endpoints of roads, and some farm can be found at every endpoint of every road. No two roads cross, and precisely one path(sequence of roads) links every pair of farms. 

After hearing about the epidemic of obesity in the USA, Farmer John wants his cows to get more exercise, so he has committed to create a bovine marathon for his cows to run. The marathon route will include a pair of farms and a path comprised of a sequence of roads between them. Since FJ wants the cows to get as much exercise as possible he wants to find the two farms on his map that are the farthest apart from each other (distance being measured in terms of total length of road on the path between the two farms). Help him determine the distances between this farthest pair of farms.

# Standard Input

* Line $1$: Two space-separated integers: $N$ and $M$

* Lines $2 \cdots M+1$: Each line contains four space-separated entities, $F1,
F2, L,$ and $D$ that describe a road. $F1$ and $F2$ are numbers of
two farms connected by a road, $L$ is its length, and $D$ is a
character that is either `N`, `E`, `S`, or `W` giving the
direction of the road from $F1$ to $F2$.

# Standard Output

Line $14: An integer giving the distance between the farthest pair of farms.

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
4 7 2 S</td><td>52</td></tr></table>


# Constraints



# Note

The longest marathon runs from farm $2$ via roads $4, 1, 6$ and $3$ to farm $5$ and is of length $20+3+13+9+7=52$.

# Source


