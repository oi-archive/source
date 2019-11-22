
# Content

All the citizens in the magic world cheer for you, the clever programmers! With your help, the war in the magic world finally ends!

Now, our hero zplinti1 is back to work. He works in a computer game company, and his new product is a war-like game, but at the most time the players just sit at their computers and watch how the war going on.

The war breaks with the United Kingdom of Red and the United Kingdom of Black. We will call them Red and Black in the following paragraphs. They will keep invading the other’s territory until one wins at last.

The map of the war is a map with n cities, and m roads connecting them, forming an undirected graph. It’s guaranteed the graph is connected. 

At first, some cities are captured by Red, some are captured by Black, and others are unoccupied. Then the cities might get united. That is, if two cities from the same country can be reached to each other without passing any city not captured by their country, they will get united and form a sub-graph. Each maximum sub-graph is called a kingdom.**The size of a kingdom is the cities the kingdom contains. The size of a country is also the cities the country contains.**

The game processes in Two steps.

#### For the First Part:

In each second, each kingdom begin to invade the unoccupied cities that are directly connected by that kingdom at the same time. For each unoccupied city, if there are more than one kingdoms invading, we judge the battle’s result in this way:

1. Check if all the biggest kingdoms (There might only be one such biggest kingdom!) among those are from the same country. If it is true, the city belongs to that country.
2.	Otherwise, among all those kingdoms invading the city, we count the total size of the kingdoms from Red and the total size of the kingdoms from Black. If they are different, the city belongs to the bigger country.
3.	Otherwise, count the total size of Red and total size of Black. If they are different, the bigger one gets the city.
4.	If it is still impossible to judge the battle’s result, the city will belong to the country Black. (I won’t tell you zplinti1 loves Bearchild very much, and `Black` and `Bearchild` all begins with letter `B`!)

After each second, the number of the kingdoms and the size of each kingdom might change, since there are more cities getting connected.

If all the cities are occupied, the Game will get into the second part.

#### For the second Part: 

Since there are no unoccupied cities on the map, two countries start to invade each other!

In each second, every kingdom will start to invade all the kingdoms that is directly connected to that kingdom, whose size is smaller, and belongs to the other country. And the invading will always succeed instantly, and all the cities of that kingdom will be captured. But all the invading happen at the same time, so while kingdom B is invading kingdom C, kingdom B’s original cities might be captured by kingdom A.

The war will end, when there can be no invading any more. Then you need to output the result of the war.

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases.$(T\leq 30)$

For each case, the first line contains two integers $n$ and $m$: the number of cities and the roads $(1\leq n\leq 100,000, 1\leq m\leq 200,000)$. Then $m$ lines follow, each with two integers $u$ and $v$, with means there is a undirected road between city $u$ and $v$ $(0\leq u, v< n)$. 

The following line contains a number $P$ $(1\leq P\leq 100)$. Then $P$ lines follow, each line with two integers $city_i$ and $from_i$. If $from_i$ equals $0$, it means $city_i$ is captured by country Red. If $from_i$ equals $1$, it means it is captured by country Black $(0\leq city_i< n, 0\leq from_i\leq 1)$. All the $city_i$ will be different. All the other cities apart from those cities are unoccupied at first.

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). If the country Red captures all the cities at last, output `Red`, if the country Black captures all the cities, output `Black`, if there is a tie, output two numbers, the first is the number of cities belonging to Red, the second is the number of the cities belonging to Black.

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
4 4
0 1
1 2
2 3
0 3
2
0 0
1 1
4 4
0 1
1 2
2 3
1 3
3
0 1
2 0
3 0
3 2
0 1
1 2
2
0 0
2 1</td><td>Case #1: 2 2
Case #2: Red
Case #3: Black</td></tr></table>


# Constraints



# Note



# Source


