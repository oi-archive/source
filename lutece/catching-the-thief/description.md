
# Content

In the Qingshui Village, there's a clever thief and a cleverer police. 

There are $N$ houses in Qingshui Village which are located in a straight line. And the $N$ houses are numbered from $1$ to $N$ according to the direction of the line. Two houses are consided to be neighbor of each other if and only if there is no other house between them.

The thief hides in one of $N$ houses now, and the police tries to find him out. Every day the police will choose a house to check and he will catch the thief if he hides in that house. If the thief survive the arrest of the police, in the night he will move to a neighboring house to pass through the next day.

What is the number of days the police needs to catch the thief in the worst case?

Remember that the police is a clever man.

# Standard Input

In the first line, an integer $T (T \leq 100)$ indicates the number of cases. 

$T$ lines follow. Each contains an integer $N$ described above. $(1 \leq N \leq 10000)$

# Standard Output

For each test case, output `Case x: d` in which $x$ is the number of test case counted from one, and $d$ is the number of days before the police catch the thief in the worst case.

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
1
2</td><td>Case 1: 1
Case 2: 2</td></tr></table>


# Constraints



# Note

Case $1$: There is only one room, so the police can catch the thief on the first day.

Case $2$: There are two rooms. The police can check room $1$ on the first day. The worst case is that the thief is in room $2$, but in this case the police can check room $1$ on the second day and will catch the thief for sure.

# Source


