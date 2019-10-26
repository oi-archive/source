
# Content

*This is the job the bear finds*

*This is the job the bear finds*

*This is the job the bear finds*

*Not with a code but a brick.*

<p class="text-right">
-- Kenneth Snow, *The Hollow Bear*
</p>

Bearchild is working in a construction team. Life is hard, and his job is just carrying bricks from here to there, what a waste of time! So, our lovely Bearchild has invented a strange machine to help him.

The machine consists three parts:  A rope, a little, round pulley (regarded as points) and a big pulley which is a convex hull (Bearchild is short of money and can't make his big pulley round!). One end of the rope is fixed with bricks, the rope goes around the small pulley, and finally connects the big pulley on its contour. It's guaranteed that the small pulley is located to the left of the big one.

You can see that when the big pulley spins clockwise around its center of gravity, the bricks will be pulled up, and finally reach the small pulley as the destination. Note that the rope will circle around the contour of the big pulley as it spins.

See the picture for more information, there will be no collision when spinning.

![title](/source/lutece/this-is-the-job-the-bear-finds/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODI0LzIwMTQwNDE3MTU0ODA2MzgyMi5qcGc=.jpg)

In this problem, first of all we let the pulley spin for one or more circles so the rope becomes tight. After that, the positions of the two pulleys are given. Then you have to deal a lot of queries, for each query, the distance from the bricks and the small pulley (also as the destination) is given. Your task is to calculate the degree the pulley has yet to spin to pull the bricks to the destination.

# Standard Input

The first line has a number $T$ ($T\leq 1000$) , indicating the number of test cases.

For each test case, first line is a number $n$, which is the number of points of the big pulley (As a convex hull). Then $n$ lines follow, each with two numbers as the $x$ and $y$ coordinate of each point. Those points are given in counter-clockwise order. Then a line with two numbers, which are the $x$ and $y$ coordinate of the small pulley. Those coordinates are in the range $[-1000000,1000000]$.

Then a number $m$ indicating the number of queries.

For next $q$ lines, each contains a number $l$ ($0<l<10^9$), which is the distance between the bricks and the small pulley.

For $90\%$ of the data, we have $n,m\leq 100$;
All the data have $n\leq 10^4$, $m\leq 10^5$, and all the numbers in the input are integers.

# Standard Output

For every case, you should output `Case #t: ` at first, without quotes. The $t$ is the case number starting from $1$.

Then $q$ lines each answers a query in the Input, which should be printed accurately rounded to three decimals.

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
4
0 0
1 0
1 1
0 1
-1 2
2
1
4
3
0 0
1 1
-1 1
-2 1
3
1
2
3</td><td>Case #1:
90.000
360.000
Case #2:
64.413
140.446
233.660</td></tr></table>


# Constraints



# Note



# Source


