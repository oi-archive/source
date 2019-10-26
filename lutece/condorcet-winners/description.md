
# Content

A Condorcet winner of an election is a candidate who would beat any of the other candidates in a one-on-one contest. Determining a Condorcet winner can only be done when voters specify a ballot listing all of the candidates in their order of preference (we will call such a ballot a preference list). For example, assume we have $3$ candidates - $A$, $B$ and $C$ - and three voters whose preference lists are $ABC$, $BAC$, $CBA$. Here, $B$ is the Condorcet winner, beating $A$ in $2$ of the three ballots (ballots $2$ and $3$) and beating $C$ in $2$ of the three ballots ($1$ and $2$).

The Condorcet voting system looks for the Condorcet winner and declares that person the winner of the election. Note that if we were only considering first place votes in the example above (as we do in most elections in the US and Canada), then there would be a tie for first place. There can be at most only one Condorcet winner, but there is one small drawback in the Condorcet system | it is possible that there may be no Condorcet winner.

# Standard Input

Input for each test case will start with a single line containing two positive integers $b$ $c$, where $b$ indicates the number of ballots and $c$ indicates the number of candidates. Candidates are considered numbered $0 \cdots c$. Following this first line will be $b$ lines containing $c$ values each. Each of these lines represents one ballot and will contain the values $0 \cdots c$ in some permuted order. Values of $b$ and $c$ will lie in the ranges $1\cdots 500$ and $1\cdots 2500$, respectively, and the line `0 0` will follow the last test case.

# Standard Output

For each test case output a single line containing either the candidate number of the Condorcet winner,or the phrase `No Condorcet winner` using the format given.

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
<tr><td>3 3
0 1 2
1 0 2
2 1 0
3 3
0 1 2
1 2 0
2 0 1
0 0</td><td>Case 1: 1
Case 2: No Condorcet winner</td></tr></table>


# Constraints



# Note



# Source


