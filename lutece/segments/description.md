
# Content

There are some segments on the plane, we assume there $4$ possible position concepts for every $2$ segments: no common point, countless common points, one common point and the point is also the endpoint of either segment, one common point but the point is not the endpoint of either segment.

# Standard Input

The first line of the input is an integer $T$, which represents that there are $T$ test cases.

An integer $n$ indicating the number of segments

$n$ line follows, $4$ integers per line, $x_1, y_1, x_2, y_2$, representing the coordinates of the endpoints of both segments .$(1 \leq n \leq 100)$

# Standard Output

For each test case, please output $4$ line, $1$ integer per line

For the first line, please output the number of pairs of segments that have no common point

For the second line, please output the number of pairs of segments that have countless common point

For the third line, please output the number of pairs of segments that have $1$ common point and the point is also the endpoint of either segment

For the fourth line, please output the number of pairs of segments that have $1$ common point and the point is not the endpoint.

After each case output a blank line include the last case.

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
3
-1 0 1 0
0 -1 0 1
-1 2 1 2
3
1 0 3 0
2 0 4 0
4 0 5 0</td><td>2
0
0
1

1
1
1
0</td></tr></table>


# Constraints



# Note



# Source


