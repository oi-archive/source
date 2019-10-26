
# Content

The country Treeland consists of $n$ cities, some pairs of them are connected with unidirectional roads. Overall there are $n-1$ roads in the country. We know that if we don't take the direction of the roads into consideration, we can get from any city to any other one.

The council of the elders has recently decided to choose the capital of Treeland. Of course it should be a city of this country. The council is supposed to meet in the capital and regularly move from the capital to other cities (at this stage nobody is thinking about getting back to the capital from these cities). For that reason if city a is chosen a capital, then all roads must be oriented so that if we move along them, we can get from city a to any other city. For that some roads may have to be inversed.

Help the elders to choose the capital so that they have to inverse the minimum number of roads in the country.

# Standard Input

There are multiple test cases. 

The first line of each test case contains integer $n$ ($2\le n\le 2\times 10^5$) — the number of cities in Treeland. Next $n-1$ lines contain the descriptions of the roads, one road per line. A road is described by a pair of integers $s\_i$, $t\_i$ ($1\le s\_i,t\_i\le n$; $s\_i\neq t\_i$) — the numbers of cities, connected by that road. The $i\_{th}$ road is oriented from city $s\_i$ to city $t\_i$. You can consider cities in Treeland indexed from $1$ to $n$.

# Standard Output

For each test case,in the first line print the minimum number of roads to be inversed if the capital is chosen optimally. In the second line print all possible ways to choose the capital — a sequence of indexes of cities in the increasing order.

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
<tr><td>16
1 2
3 2
4 1
5 3
6 1
2 7
1 8
4 9
10 4
11 2
12 9
5 13
14 2
15 7
3 16</td><td>7
10</td></tr></table>


# Constraints



# Note



# Source


