
# Content

The year is 2014. Mankind has come a long way since
that crucial day in 2013 when genius students wrote those
groundbreaking programs at IDI Open. Travelling in space
has become as normal as feeding your personal crocodile;
something you never do more than once...

You want to do something about this, and have
identified the problem with space travel to it being too time
consuming. You therefore decide to write a program that
finds the optimal (shortest in time) travel route between
two points in three dimensional space.

This is made somewhat more complex due to the
existence of worm tubes. A space traveller can enter a worm tube at any point (on
it) and leave at any point. This process takes no time at all. A worm tube is modelled as
a line segment in a three dimensional space.

Other than in worm tubes, travel time is proportional to the distance travelled.

# Standard Input

The first line contains $T$, the number of test cases that follow. Each test case starts with
a line containing an integer $N$, the number of worm tubes in space. Then follows a line
containing three integers $s\_x$, $s\_y$ and $s\_z$, the starting point for the route you're going to
find the optimal route for. Then follow a line containing the corresponding end point, $e\_x$,
$e\_y$ and $e\_z$.

After that follow $N$ lines, describing the $N$ worm tubes. Each worm tube is described
by $6$ integers $sx\_i$, $sy\_i$, $sz\_i$, $ex\_i$, $ey\_i$ and $ez\_i$, describing the start and end point of that tube.

$0 < T \le 50$

$0 \le N \le 50$

$0 < p\_x, p\_y, p\_z \le 1000$, for all $s$ and $e$.

The two end points of a worm tube are not equal.

Any output with a relative or absolute error of $10^{-6}$ is accepted.

# Standard Output

For each test case, output a single 
floating point number; the distance travelled outside
of worm tubes in the optimal route.

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
0
10 12 15
9 11 16
2
100 100 100
123 126 129
102 109 103 110 120 113
108 121 104 120 125 122</td><td>1.7320508075688772
21.56720748874348</td></tr></table>


# Constraints



# Note



# Source


