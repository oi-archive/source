
# Content

Dynamic Query System (`DQS`) is a system can manage integers. 

It have $8$ kinds of commands as follow:
1. `I X` : insert an integer $X$ into this system.
2. `R X` : remove integer $X$ from this system, if the number 
of $X$ is greater than $1$ , just remove one of them,
and if $X$ does not exist, do nothing.
3. `S` : print the number of the integers in the system 
in a single line.
4. `L X` : print the number of the integers which are less
than $X$ in a single line.
5. `W K` : print the $K\_{th}$($1$-based) integer in a single line 
if the integers are sorted by ascending order.
if $K$ is zero or $K$ is larger than the number of the
integers in the system, just output $-1$.
6. `C X` : print the number of $X$ in this system.
7. `MI` : print the minimum integer of the system in a 
single line. if the answer does not exist, just output $-1$.
8. `MA` : print the maximum integer of the system in a
single line. if the answer does not exist, just output $-1$.

# Standard Input

The first line of the input is an integer $T$ which stands
for the number of test cases. Then $T$ test cases follow.

The first line of test case is a number $N$, which is the 
number of commands. Then n commands follow, and each 
command is in a single line.

constraints:
* $X$ is in the range of $[0, 100000000)$.
* $K$ is in the range of $[0, 100000000)$.
* $N$ is in the range of $[0, 500000]$.

# Standard Output

Simulate the DQS, and the output is the output of DQS.

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
6
I 1
I 2
S
C 2
MI
MA</td><td>2
1
1
2</td></tr></table>


# Constraints



# Note



# Source


