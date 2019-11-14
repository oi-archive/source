
# Content

Thomas T. Garmin got a GPS for his birthday last year, and he loved it! Unfortunately, sometimes Tom wanted to take a scenic route rather than the shortest one as suggested by the GPS. He did a little reading in the manual and found that he could override the default path-finding algorithm by specifying roads which the GPS system would be forced to use when determining a route. After some experimentation, Tom discovered that often, forcing a single road succeed to get the desired route.However, for some windier routes, Tom needed to force more roads. Eventually Tom began to worry that he wasted too much time picking roads to force before each trip. Now, instead of enjoying the wonders of his GPS, he spends his drives agonizing over the following question: could he have gotten his GPS to pick the scenic route using fewer forced roads? Can you save this love affair, or are Tom and his GPS doomed to walk separate paths?

# Standard Input

Input for each test case will consist of a number of lines. The first line will contain a single integer $n < 100$ indicating the number of endpoints for the roads, numbered $0$ to $n$. There will then follow $n$ lines each containing $n$ non-negative integers. If the $j\_{th}$ value in row $i$ is positive, it indicates the length of a road from endpoint $i$ to endpoint $j$; if the value is $0$, it indicates that there is no road between those two endpoints. Following these lines will be a line of the form $m$ $p\_1$ $p\_2$ $p\_3$ $\cdots$ $p\_m$ specifying the scenic route that Tom wants { the route contains $m$  roads and goes between endpoints $p\_1$ and $p\_m$,visiting endpoints $p\_2$, $p\_3$, etc., in that order. The last test case will be followed by a line containing $0$.

Note that when Tom specifies his forced roads to his GPS, he specifies both their direction and order.

All the routes are simple paths and all roads lengths are $\le 100$.

# Standard Output

For each test case one line of output as follows:
`Case n: k`
where $k$ is the smallest number of roads Tom must force such that the GPS will choose the specified route. You should assume that if there are multiple shortest paths, the GPS always selects the most scenic of these. Therefore, if Tom's route is among the shortest to use a given set of forced roads, it will be picked by the GPS.

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
0 4 0 2
4 0 2 0
0 2 0 2
2 0 2 0
4 0 3 2 1
0</td><td>Case 1: 1</td></tr></table>


# Constraints



# Note



# Source


