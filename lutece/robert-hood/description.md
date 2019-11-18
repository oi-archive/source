
# Content

Robert Hood, a less famous sibling of the Robin Hood, is fed up. Despite him being a young, talented archer he never seems to reach quite the same level as his legendary brother, and so he decided to come up with rules for a new archery contest, in which he will stand a better chance of winning. 

The rules for the new kind of archery contest are quite simple: the winner is no longer the one who can score the most points, but instead the one who can achieve the longest distance between any pair of arrows hitting the target. Your task is to write the code to calculate that distance.

A contestant is allowed a number of arrow shots, and the coordinates of the arrows successfully hitting the target are given as a list of pairs. The coordinate system is Cartesian with the origin in the centre of the archery butt. If a contestant does not hit the target with at least two arrows he or she is disqualified and removed from the input data.

Your task is to calculate the score for a contestant that has not been disqualified.

# Standard Input

The input starts with a line containing a single positive integer $C, 2 \leq C \leq 100 000$, representing the number of shots successfully hitting the target for this particular contestant. Each following line contains a pair of integer coordinates separated by a space, representing the $x$- and $y$-coordinates of a successful shot. The absolute value of any coordinate does not exceed $1 000$.

# Standard Output

Print the longest distance between any pair of arrows as a floating point number on a single line. The answer is considered correct if it has a relative or absolute error of less than $10^{-6}$.

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
2 2
-1 -2</td><td>5.0</td></tr><tr><td>5
-4 1
-100 0
0 4
2 -3
2 300</td><td>316.86590223</td></tr></table>


# Constraints



# Note



# Source


