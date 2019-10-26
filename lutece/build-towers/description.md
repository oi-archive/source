
# Content

Build towers on a game board is very interesting. Here we introduce one kind of game which is also building towers on the game board.

![title](/source/lutece/build-towers/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTIxNi8yMDE1MTAyMDE3NDQwMTI0MzQucG5n.png)

There are $n$ sticks on the game board. At the beginning of the game, we put plates of different colors on the sticks. There are $n - 2$ different colors of plates. For each color,
there are plates of size $0$, $1$, $2$, $3$, $4$, $5$, $6$. One for each size. So totally there are $7(n - 2)$ plates put on the sticks.

If a plate of size $x$ is put right above the plate of size $x + 1$ of the same color, they are glued together and not able to be split any more. In other words, they must be moved
together in the rest of the game.

For each move, we can only move the top plate of each stick, maybe it's glued with several other plates, so they will be moved together. We can only move them onto a stick that the
top plate is in the same color with the moving one and is larger than the moving plates. Or we can move them onto an empty stick.

The goal of this game is to make $n - 2$ towers on any of the $n - 2$ different sticks. Each of them are made of $7$ plates in the order of $0$, $1$, $2$, $3$, $4$, $5$, $6$
from top to bottom.

Now you need to find the minimal number of moved to achieve this.

# Standard Input

The first line of the input gives the number of test cases, $T$($1\leq T\leq 20$). $T$ test cases follow. Each test case starts with number $n$($n = 8$), the number of sticks on
the game board. Each of the next $n$ lines starts with a number $P\_i$($1\leq P\_i\leq 6$) represents the number of plates set on each stick. $P\_i$ strings follow, each represents a plate set on
that stick from bottom to top. The first character of the string represents the color and the rest represents the size or size range.

It's guaranteed that the number of colors equals $n-2$ and there are $7$ different plates for each color, $0$ to $6$.

It's also guaranteed that there exists at least one solution for each test case.

# Standard Output

For each test case, output one line containing `Case #x: y`, where $x$ is the test case number (starting from $1$) and $y$ is the minimal number of moves to make $n - 2$
complete towers.

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
<tr><td>1
8
6 A0 B0 E1 C0 C5 F3
6 F6 D0 B4 E0 D6 C2
5 F0 B3 E5 C1 B5
5 D5 B1 E6 B2 A5
5 F1 A4 F4 D3 B6
5 A6 D2 E4 D1 C4
4 A1 E2-3 D4 A2
5 A3 C6 F5 C3 F2</td><td>Case #1: 47</td></tr></table>


# Constraints



# Note



# Source


