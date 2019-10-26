
# Content

The earth is under an attack of a deadly virus. Luckily, prompt actions of the Ministry of
Health against this emergency successfully confined the spread of the infection within a square
grid of areas. Recently, public health specialists found an interesting pattern with regard to the
transition of infected areas. At each step in time, every area in the grid changes its infection
state according to infection states of its directly (horizontally, vertically, and diagonally) adjacent areas.

* An infected area continues to be infected if it has two or three adjacent infected areas.
* An uninfected area becomes infected if it has exactly three adjacent infected areas.
* An area becomes free of the virus, otherwise.

Your mission is to fight against the virus and disinfect all the areas. The Ministry of Health
lets an anti-virus vehicle prototype under your command. The functionality of the vehicle is
summarized as follows.

At the beginning of each time step, you move the vehicle to one of the eight adjacent areas.
The vehicle is not allowed to move to an infected area (to protect its operators from the
virus). It is not allowed to stay in the same area.

Following vehicle motion, all the areas, except for the area where the vehicle is in, change
their infection states according to the transition rules described above.

Special functionality of the vehicle protects its area from virus infection even if the area
is adjacent to exactly three infected areas. Unfortunately, this virus-protection capability
of the vehicle does not last. Once the vehicle leaves the area, depending on the infection
states of the adjacent areas, the area can be infected.

The area where the vehicle is in, which is uninfected, has the same effect to its adjacent
areas as an infected area as far as the transition rules are concerned.

The following series of figures illustrate a sample scenario that successfully achieves the goal.
Initially, your vehicle denoted by `@` is found at $(1, 5)$ in a $5\times 5$-grid of areas, and you see some infected areas which are denoted by `#`’s.

![title](/source/lutece/infected-land/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjEzLzIwMTQwMzE3MjEyNTQ4MTg5MS5qcGc=.jpg)

Firstly, at the beginning of time step $1$, you move your vehicle diagonally to the southwest,
that is, to the area $(2, 4)$. Note that this vehicle motion was possible because this area was not
infected at the start of time step $1$.

Following this vehicle motion, infection state of each area changes according to the transition
rules. The column “$1$-end” of the figure illustrates the result of such changes at the end of time step $1$. Note that the area $(3, 3)$ becomes infected because there were two adjacent infected areas and the vehicle was also in an adjacent area, three areas in total.

In time step $2$, you move your vehicle to the west and position it at $(2, 3)$.
Then infection states of other areas change. Note that even if your vehicle had exactly three
infected adjacent areas (west, southwest, and south), the area that is being visited by the vehicle is not infected. The result of such changes at the end of time step $2$ is as depicted in “$2$-end”.

Finally, in time step $3$, you move your vehicle to the east. After the change of the infection
states, you see that all the areas have become virus free! This completely disinfected situation
is the goal. In the scenario we have seen, you have successfully disinfected all the areas in three time steps by commanding the vehicle to move $(1)$ southwest, $(2)$ west, and $(3)$ east.

Your mission is to find the length of the shortest sequence(s) of vehicle motion commands that
can successfully disinfect all the areas.

# Standard Input

The input is a sequence of datasets. The end of the input is indicated by a line containing a
single zero. Each dataset is formatted as follows.

Here, n is the size of the grid. That means that the grid is comprised of $n\times n$ areas. You
may assume $1\leq n\leq 5$. The rest of the dataset consists of $n$ lines of $n$ letters. Each letter $a\_{ij}$
specifies the state of the area at the beginning: `#` for infection, `.` for free of virus, and `@` for the initial location of the vehicle. The only character that can appear in a line is `#`, `.`, or `@`.Among $n\times n$ areas, there exists exactly one area which has `@`.

# Standard Output

For each dataset, output the minimum number of time steps that is required to disinfect all the
areas. If there exists no motion command sequence that leads to complete disinfection, output
$-1$. The output should not contain any other extra character.

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
...
.@.
...
3
.##
.#.
@##
3
##.
#..
@..
5
....@
##...
#....
...#.
##.##
5
#...#
...#.
#....
...##
..@..
5
#....
.....
.....
.....
..@..
5
#..#.
#.#.#
.#.#.
....#
.#@##
5
..##.
..#..
#....
#....
.#@..
0</td><td>0
10
-1
3
2
1
6
4</td></tr></table>


# Constraints



# Note



# Source


