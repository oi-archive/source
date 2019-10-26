
# Content

A group of survivors has arrived by helicopter to an isolated island. The island is made up of a long narrow strip of villages. The infected survivors arrived in the village to the far east and accidentally infected the native population. The islanders are now attempting to escape the zombies that have appeared on the east coast.

You are given N cases with $20$ non-negative integers that represent the number of islanders at a given village. The villages are represented from west to east (left to right, respectively), with the zombies moving in from the east. The islanders have peculiar customs for traveling and will only move between villages in pairs. Curiously, for every pair that travels between two villages, only one of them ever survives the trip. As the zombies move west, islanders will travel to the village immediately west of their current village as long as there are at least two islanders there. If there are an odd number people in a village then one stays in the village and the rest move to the next village in pairs. Once the islanders reach the village on the west coast, they will stop traveling.

Determine how many islanders remain at each village and the number that make it safely to the village on the west coast (far left).

# Standard Input

The first line of data represents the number of data sets you will read in, $N (1 \leq N \leq 50)$.

There will then be $N$ lines of twenty $20$ non-negative integers each. Each integer ($ \leq 1000$) represents the number of islanders who reside in a village. The leftmost integer represents the village on the west coast, and the rightmost integer represents the village on the east coast.

# Standard Output

Your output will be $N$ lines of twenty $20$ non-negative integers. The left most number will represent the number of islanders that reached the west. Each number to the right will represent the number of people that stayed behind in each village.

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
0 0 0 0 77 0 0 99 0 0 0 40 0 0 0 17 0 1 13 10</td><td>5 1 0 0 1 1 0 1 1 0 0 1 0 0 1 1 1 0 0 0</td></tr></table>


# Constraints



# Note



# Source


