
# Content

Bessie wants to navigate her spaceship through a dangerous asteroid field in the shape of an $N \times N$ grid $(1 \leq N \leq 500)$. The grid contains $K$ asteroids $(1 \leq K \leq 10,000)$, which are conveniently located at the lattice points of the grid.

Fortunately, Bessie has a powerful weapon that can vaporize all the asteroids in any given row or column of the grid with a single shot.This weapon is quite expensive, so she wishes to use it sparingly.Given the location of all the asteroids in the field, find the minimum number of shots Bessie needs to fire to eliminate all of the asteroids.

# Standard Input

The first line contains a single integer $t (1 \leq t \leq 11)$, the number of test cases.

Each case begins with two integers $N$ and $K$, separated by a single space.Then $K$ lines follows,each line contains two space-separated integers $R$ and $C (1 \leq R, C \leq N)$ denoting the row and column coordinates of an asteroid, respectively.

# Standard Output

For each case, print an integer representing the minimum number of times Bessie must shoot.

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
3 4
1 1
1 3
2 2
3 2</td><td>2</td></tr></table>


# Constraints



# Note

#####INPUT DETAILS:
The following diagram represents the data, where `X` is an asteroid and `.` is empty space:
```
X.X
.X.
.X.
```
#####OUTPUT DETAILS:
Bessie may fire across row $1$ to destroy the asteroids at $(1,1)$ and $(1,3)$, and then she may fire down column $2$ to destroy the asteroids at $(2,2)$ and $(3,2)$.

# Source


