
# Content

A well known puzzle consists of $7$ hexagonal pieces, each with the numbers $1$ through $6$ printed on the sides. Each piece has a different arrangement of the numbers on its sides, and the object is to place the $7$ pieces in the arrangement shown below such that the numbers on each shared edge of the arrangement are identical. Figure (a) is an example of one solution:
 
![title](/source/lutece/hexagon-perplexagon/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjcyLzIwMTQwODMwMTEyNTA2NzA1MzAucG5n.png)

#####Notation for Output
Rotating any solution also gives another trivially identical solution. To avoid this redundancy, we will only deal with solutions which have a $1$ on the uppermost edge of the central piece, as in the example.



# Standard Input

The first line of the input file will contain a single integer indicating the number of test cases. Each case will consist of a single line containing $42$ integers. The first $6$ represent the values on piece $0$ listed in clockwise order; the second $6$ represent the values on piece $1$, and so on.

# Standard Output

For each test case, output the case number (using the format shown below) followed by either the phrase

No solution or by a solution specification. A solution specification lists the piece numbers in the order shown in the Position Notation of Figure (b). Thus if piece $3$ is in the center, a $3$ is printed first; if piece $0$ is at the top, $0$ is printed second, and so on. Each test case is guaranteed to have at most one solution.

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
3 5 6 1 2 4 5 1 2 3 6 4 2 3 5 4 1 6 3 1 5 6 2 4 5 4 1 3 6 2 4 2 3 1 5 6 3 6 1 2 4 5
6 3 4 1 2 5 6 4 3 2 5 1 6 5 3 2 4 1 5 4 6 3 2 1 2 5 6 1 4 3 4 6 3 5 2 1 1 3 5 2 6 4</td><td>Case 1: 3 0 5 6 1 4 2
Case 2: No solution</td></tr></table>


# Constraints



# Note



# Source


