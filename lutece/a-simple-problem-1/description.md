
# Content

You know, just as the title imply, this is a simple problem.

In a contest, given the team-id, solved, penalty of all the teams, tell me the champion.If the numbers of solved problem of two team are different, the rank of the one who solves more problems is higher. Otherwise, if the the penalties of two team are different, the rank of the one who has less penalty is higher. Otherwise, the rank of the one whose team-id's lexicographic order is earlier than the other is higher.

# Standard Input

The first line of the input is an integer $T$ which stands for the number of test cases. Then $T$ test cases follow.

The first line of test case is a number $n$, which is the number of team in a contest. Then $n$ line(s) follow. Each line contain a string, and two integers: $str$, $s$($0\leq s \leq 15$), $p$($0\leq p \leq 20000$), separated by a blank indicating that there is a team whose id is str, the number of solved problem is s, and the penalty is $p$.

constraints:
* $n$ is in the range of $[1,100]$.
* Each team-id does not contain any blanks.
* The length of team-id is in the range of $[1, 20]$.
* Any two teams will not have the same team-id.

# Standard Output

For each test case, output one line with an string indicating the the champion.

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
7
Refreshing 5 745 
Rock_Restart 4 510 
LeadWill 4 679 
APTX4869 5 374 
WaterCop 5 607 
ISAP 5 638 
TLE 4 902</td><td>APTX4869</td></tr></table>


# Constraints



# Note



# Source


