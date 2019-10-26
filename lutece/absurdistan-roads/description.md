
# Content

The people of Absurdistan discovered how to build roads only last year. After the
discovery, every city decided to build their own road connecting their city with another city.
Each newly built road can be used in both directions.

Absurdistan is full of surprising coincidences. It took all $N$ cities precisely one year to build their
roads. And even more surprisingly, in the end it was possible to travel from every city to every
other city using the newly built roads.

You bought a tourist guide which does not have a map of the country with the new roads. It only
contains a huge table with the shortest distances between all pairs of cities using the newly built
roads. You would like to know between which pairs of cities there are roads and how long they are,
because you want to
reconstruct the map of the $N$ newly built roads from the table of shortest distances.

You get a table of shortest distances between all pairs of cities in Absurdistan using the $N$
roads built last year. From this table, you must reconstruct the road network of Absurdistan.
There might be multiple road networks with $N$ roads with that same table of shortest distances,
but you are happy with any one of those networks.

# Standard Input

For each test case:

* A line containing an integer $N$ $(2\le N\le 2000)$ -- the number of cities and roads.
* $N$ lines with $N$ numbers each. The $j$-th number of the $i$-th line is the shortest distance
  from city $i$ to city $j$. All distances between two distinct cities will be positive and at most
  $1\,000\,000$. The distance from $i$ to $i$ will always be $0$ and the distance from $i$ to $j$
  will be the same as the distance from $j$ to $i$.

# Standard Output

For each test case:

* Print $N$ lines with three integers '$a$ $b$ $c$' denoting that there is a
    road between cities $1 \le a \le N$ and $1 \le b \le N$ of length $1 \le c \le 1\,000\,000$, where
    $a \not = b$. If there are multiple solutions, you can print any one and you can print the roads in
    any order. At least one solution is guaranteed to exist.

Print a blank line between every two test cases.

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
<tr><td>4
0 1 2 1
1 0 2 1
2 2 0 1
1 1 1 0
4
0 1 1 1
1 0 2 2
1 2 0 2
1 2 2 0
3
0 4 1
4 0 3
1 3 0</td><td>2 1 1
4 1 1
4 2 1
4 3 1

2 1 1
3 1 1
4 1 1
2 1 1

3 1 1
2 1 4
3 2 3</td></tr></table>


# Constraints



# Note



# Source


