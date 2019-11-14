
# Content

The math teacher Fish Nineone assigned Delta homework. Delta is given a set of $N$ integers. The requirement is find the minimum number of intergers inserting to the set that for every two integers $A$ and $B$ in set, $A \oplus B$ ( bitwise exclusive OR ) is also in the set.

Delta is poor in math, so that she asks you to solve this problem to get one `Accepted`  in the 16th UESTC programming contest.

# Standard Input

The first line is an integer $T$, which indicates the number of testcases.

For each testcase:

The first line of the input file contains the integer $N$ ( $1 \leq N \leq 2 \cdot 10^5$ ).

In the second line, $N$ numbers follow ( $0 \leq a_i \leq 10^{18}$ ).

You can assume that $\sum N \leq 2 \cdot 10^6$.

# Standard Output

For each testcase, your program should output the minimum number of intergers inserting in one line.

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
3
2 4 6</td><td>1</td></tr><tr><td>1
5
2 4 5 7 11</td><td>11</td></tr></table>


# Constraints



# Note

In the second example, all numbers from 0 to 15 should in the set.

number $8$ is in the set as follow:

$4 \oplus 5 = 1$,

$1 \oplus 2 = 3$,

$3 \oplus 11 = 8$
...

# Source


