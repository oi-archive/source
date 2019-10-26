
# Content

Nemo is a naughty boy. One day he went into the deep sea all by himself. Unfortunately, he became lost and couldn't find his way home. Therefore, he sent a signal to his father, Marlin, to ask for help.

After checking the map, Marlin found that the sea is like a labyrinth with walls and doors. All the walls are parallel to the $X$-axis or to the $Y$-axis. The thickness of the walls are assumed to be zero.

All the doors are opened on the walls and have a length of $1$. Marlin cannot go through a wall unless there is a door on the wall. Because going through a door is dangerous (there may be some virulent medusas near the doors), Marlin wants to go through as few doors as he could to find Nemo.

Figure-$1$ shows an example of the labyrinth and the path Marlin went through to find Nemo. 

![title](/source/lutece/finding-nemo/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDAzLzIwMTQwODEyMjI0NzIwNTU4Ni5qcGc=.jpg)

We assume Marlin's initial position is at $(0, 0)$. Given the position of Nemo and the configuration of walls and doors, please write a program to calculate the minimum number of doors Marlin has to go through in order to reach Nemo.

# Standard Input

The first line of the input is an integer $T$ ($T \leq 100$), which stands for the number of test cases you need to solve.

Each test case is started by two non-negative integers $M$ and $N$. $M$ represents the number of walls in the labyrinth and $N$ represents the number of doors.

Then follow $M$ lines, each containing four integers that describe a wall in the following format:`x y d t`

$(x, y)$ indicates the lower-left point of the wall, $d$ is the direction of the wall -- $0$ means it's parallel to the $X$-axis and $1$ means that it's parallel to the $Y$-axis, and $t$ gives the length of the wall.

The coordinates of two ends of any wall will be in the range of $[1,199]$.

Then there are $N$ lines that give the description of the doors:`x y d`
$x, y, d$ have the same meaning as the walls. As the doors have fixed length of $1$, $t$ is omitted.

The last line of each case contains two positive float numbers:`f1 f2`
$(f\_1, f\_2)$ gives the position of Nemo. And it will not lie within any wall or door.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. please output the minimum number of doors Marlin has to go through in order to rescue his son. If he can't reach Nemo, output $-1$.

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
8 9
1 1 1 3
2 1 1 3
3 1 1 3
4 1 1 3
1 1 0 3
1 2 0 3
1 3 0 3
1 4 0 3
2 1 1
2 2 1
2 3 1
3 1 1
3 2 1
3 3 1
1 2 0
3 3 0
4 3 1
1.5 1.5
4 0
1 1 0 1
1 1 1 1
2 1 1 1
1 2 0 1
1.5 1.7</td><td>Case #1: 5
Case #2: -1</td></tr></table>


# Constraints



# Note



# Source


