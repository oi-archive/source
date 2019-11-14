
# Content

There are $N$ parallel streets, each with $M$ street lamps, every day when it's about to dawn, you'll have to turn all of them off, the problem is, the lamps are wired in a strange way and turning off one lamp could affect others lamps' on-off states! Some of the lamps of the same street are wired but some are not, so turning on or off may make the lamp direct connecting to it change state (from on to off and vice versa).

Given a state of the wirings and of the street lamps, find the minimum number of switch turn all the lamps off!

# Standard Input

The first line is $T$ ($T\leq 50$), the number of test cases.

For each case, the first line containing $2$ integers: $N$, $M$ ($0 < N\leq 100$ and $0 < M\leq 10$). Then $2N - 1$ lines followed, describing the lamps and the wires between them. Each line is a street with m lamps, `o` represent a lit lamp while `*` represent a lamp that already be turned off, `|` and `-` represent a wire that connecting two neighboring lamps. And the `\` ,`/` indicates a wire sideling connecting. And `X` indicates two wires sideling connecting. For more details, please read the hint for test case.

# Standard Output

For each case, output `Case d: x`, where $d$ is the case number counted from one, and $x$ is an integer represents the minimum number of switch to turn all the lamps off! If no method to turn all the lamps off, please output `-1` instead of $x$.

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
2 2
*-o

o-*
2 2
*-o
 \ 
o-*
2 3
o o o
 X X 
o o o</td><td>Case 1: -1
Case 2: 2
Case 3: 2</td></tr></table>


# Constraints



# Note

In the second test case, you can switch the light $(0, 0)$ and $(1, 1)$ to turn all the lights off.

In the third test case, you can switch the light $(0, 1)$ and $(1, 1)$ to turn all the lights off.

# Source


