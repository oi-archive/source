
# Content

Magic Cube is a cube (M $\cdot$ M $\cdot$ M) which contains a integer number (0 $\leq$ number < P) in each sell (So you know there are $M^3$ numbers).

Alice have one big cube and N smaller cubes (each small cube is unique),

The cube is magic since when you put a small cube in bigger one, the number in the same location will add up and mod P.

You job is to determine the location of each cube, so that we can make every number in big cube equal 0 after putting all the small cubes.

Note:

1. We guarantee that there is only one solution.

2. You cannot rotate cube.

3. We give the numbers in cubes in order of position [0, 0, 0], [0, 0, 1], ..., [0, 1, 0], ..., [1, 0, 0], ...

# Standard Input

The first line is three integers M (2 $\leq$ M $\leq$ 7), N (1 $\leq$ N $\leq$ 12), P (3 $\leq$ P $\leq$ 5)

Second line is M $\cdot$ M $\cdot$ M integers, showing the numbers in big cube.

Then is N lines, which first is a integer L[i] (1 $\leq$ L[i] < M) shows the length of the small cube, then follows $L[i]^3$ numbers (0 $\leq$ number < P).

# Standard Output

Output N lines of triad of integers, shows the location of this small cube.

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
<tr><td>2 1 3
1 0 0 0 0 0 0 0
1 2</td><td>0 0 0</td></tr></table>


# Constraints



# Note



# Source


