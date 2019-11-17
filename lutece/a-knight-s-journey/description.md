
# Content

![title](/source/lutece/a-knight-s-journey/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDAyLzIwMTQwODEyMjIzOTQ0MjQ3NS5qcGc=.jpg)

####Background
The knight is getting bored of seeing the same black and white squares again and again and has decided to make a journey
around the world. Whenever a knight moves, it is two squares in one direction and one square perpendicular to this. The world of a knight is the chessboard he is living on. Our knight lives on a chessboard that has a smaller area than a regular $8 \times 8$ board, but it is still rectangular. Can you help this adventurous knight to make travel plans?

####Problem
Find a path such that the knight visits every square once. The knight can start and end on any square of the board.

# Standard Input

The input begins with a positive integer $n$ in the first line. The following lines contain $n$ test cases. Each test case consists of a single line with two positive integers $p$ and $q$, such that $1 \leq p \times q \leq 26$. This represents a $p \times q$ chessboard, where $p$ describes how many different square numbers $1, \cdots , p$ exist, $q$ describes how many different square letters exist. These are the first $q$ letters of the Latin alphabet: `A`,$\cdots$

# Standard Output

The output for every scenario begins with a line containing `Scenario #i:`, where $i$ is the number of the scenario starting at $1$. Then print a single line containing the path with the largest lexicographically order that visits all squares of the chessboard with knight moves followed by an empty line. The path should be given on a single line by concatenating the names of the visited squares. Each square name consists of a capital letter followed by a number.

If no such path exist, you should output impossible on a single line.

Output a single line after each case.

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
1 1
2 3</td><td>Scenario #1:
A1

Scenario #2:
impossible</td></tr></table>


# Constraints



# Note



# Source


