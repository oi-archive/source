
# Content

The Zombie Apocalypse is here! Zombies are quite easy to kill; however, ammunition is scarce so we need to maximize the explosive potential. Our most powerful defensive weapon is an automated grenade launcher that can identify zombified targets at extreme distances. The one missing piece is the code for optimizing the blasts to hit multiple targets.

For each known group of zombies, you will be given a kill radius and the locations of the zombies. The program should identify a coordinate to hit with the explosive to kill as many zombies as possible and output the maximum number of targets that can be killed with one round. A zombie will be killed if its distance from the explosive is equal to or less than the kill radius.

# Standard Input

he first line of input will contain an integer representing the number of test cases, $C (1 \leq C \leq 20)$. For each test case, there will be a single line containing a kill radius as a real number, $R (0 < R \leq 1000.0)$, and a count of zombie targets, $N (0 \leq N \leq 25)$, followed by N lines containing a pair of Cartesian coordinates $X$ $Y (-10^6 \leq X, Y \leq 10^6)$ giving each zombie position. The units used for the kill radius and the coordinates are both in meters.

$C$

$R$ $N$

$X\_0$ $Y\_0$

$ \cdots$

$X\_{N-1}$ $Y\_{N-1}$

# Standard Output

Output will be a single line per test case with the number of targets that can be killed with a single explosive round. Output for each test case should be on its own line.

$K\_0$

$ \cdots $

$K\_{C-1}$

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
3 5
1 0
0 0
0 1
1 1
5 5
1.0 1
1.0 0.0</td><td>4
1</td></tr></table>


# Constraints



# Note



# Source


