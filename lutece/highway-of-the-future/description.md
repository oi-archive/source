
# Content

It is the year 23413 and the quantum road authority (QRA) needs your
help designing a new quantum highway.
The biggest difference between a quantum highway and a
regular highway is that quantum cars can switch lanes instantly,
i.e. at $t\_1$ a quantum car can be in one lane, while (as long as
$t\_1 \neq t\_2$) at $t\_2$ it can be in another.

Of course, in the year 23413 the future prediction authority (FPA)
has information on exactly who will be using this new highway.
For each quantum car that will travel along your quantum highway,
the FPA supplies you with a value $t$, which is the time at which
the quantum car will enter your highway, and a value $v$ which
represents the speed at which the quantum car will travel along
your quantum highway.

The length of your highway will be $100$ length units.
In one time unit, a quantum car going at a speed of $v$ speed units,
will have travelled exactly $v$ length units.
The size of a quantum car is negligible compared to the length of
your highway; it should be considered as a point.

Your job is to make sure that there will be no collisions on this
quantum highway. Quantum cars are equipped with very sophisticated
collision prevention mechanisms: as long as there are enough lanes
in your quantum highway, cars will "magically'' switch lanes
to avoid collisions.
A collision still occurs if, at any time, the number of cars at a particular position along the highway exceeds the number of lanes.
Such collisions can happen even at the exact begin or end of the highway, as the sample cases illustrate.

What is the least number of lanes required to make sure there will
be no collisions?

# Standard Input

For each test case:
* A line containing one integer $n$ ($1 \le n \le 35\,000$): the number of quantum cars that will travel on your highway.
* $n$ lines containing two integers:
  * $t_i$: the time at which quantum car $i$ enters your quantum highway \\ ($1 \le t\_i \le 10\,000$).
  * $v_i$: the speed of quantum car $i$ ($1 \le v\_i \le 100$).

# Standard Output

For each test case, print one line containing one integer:
the number of lanes required to make sure there will be no collisions.

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
15 20
19 100
10 10
3
10 20
10 10
10 30
2
10 10
10 10
2
10 1
20 100</td><td>3
3
2
2</td></tr></table>


# Constraints



# Note



# Source


