
# Content

In the Game Civilization X, the world is made up of square-shaped `tiles`, forming a rectangle on the world map. For a tile located at row $X$ and column $Y$, we give it a coordinate, say ($X$, $Y$).

As you can see, different tiles have different `terrain-types`, so they may have different amount of Resources. In this problem, we only consider two of them: Food and Productivity.

An important step in the Game is building cities. After you choose a tile to build a city, the Food amount in that tile will increase by $A$, and the Productivity amount will increase by $B$, no other tiles will be changed.

You decide to build your first city on the map, as an experienced player, you will choose the best tile on the map, here is how you make up your mind:

For each tile ($X$, $Y$), you set up an `Influence Range` of that tile. Each tile ($x\_i$, $y\_i$) is said to be within the range if the following equation holds:
$$max(\left | X - x\_i \right |, \left | Y - y\_i \right |) \leq R$$

After checking all the tiles within that range, you will get two values: the sum of all those tiles' Food amount, and the sum of all those tiles' Productivity. Among those two values, the final score for tile ($X$, $Y$) will be the smaller one. 

When choosing tiles, you just choose the tile with the highest score to build your city.

You are given a map with size $N\times M$, and you wonder, for different values of $A$ and $B$, what is the highest score for your first city?

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

For each test case, first line has four numbers $N$, $M$, $R$ and $Q$ ($1 \leq N$, $M \leq 500$, $0\leq 2\times R + 1 \leq min(N,M)$, $Q \leq 200000$), which is the size of the map.

Then come $N$ lines each with $M$ numbers, they are the original $Food$ ($0 < Food \leq 3$) amount for each tile.

Then come $N$ lines each with $M$ numbers, they are the original $Productivity$ ($0 < Productivity \leq 3$) amount for each tile.

Then come $Q$ lines each with two numbers $A$ and $B$ ($0 \leq A$, $B\leq 10^6$). Each is a query for you to answer. Those queries will not affect each other.

# Standard Output

For test case $X$, output `Case #X: ` first, in a single line.

Then output $Q$ lines, each with an answer.

There should be a blank line **``BETWEEN``** each test case.

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
<tr><td>1
3 3 0 2
1 2 1
1 1 1
1 1 1
1 1 1
1 2 1
1 1 1
1 2
2 1</td><td>Case #1:
3
3</td></tr></table>


# Constraints



# Note



# Source


