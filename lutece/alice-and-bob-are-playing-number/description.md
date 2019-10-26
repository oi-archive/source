
# Content

-Bob and his girl friend are playing game together.This game is like this:

There are $n$ numbers.

If op = $1$,Bob wants to find two numbers $a_i$ and $a_j$,that $a_i$ & $a_j$ will become maximum value.

If op = $2$,Bob wants to find two numbers $a_i$ and $a_j$,that $a_i$ ^ $a_j$ will become maximum value.

If op = $3$,Bob wants to find two numbers $a_i$ and $a_j$,that $a_i$ | $a_j$ will become maximum value.

Notice:

& for bitwise AND. (4 & 2) is 0, (4 & 5) is 4.

^ for bitwise XOR. (4 ^ 2) is 6, (4 ^ 5) is 1.

| for bitwise OR . (4 | 2) is 6, (4 | 5) is 5.

# Standard Input

-First line is a positive integer $T$ , represents there are $T$ test cases.

For each test case:

First line includes two numbers $n (2 ?\leq?n?\leq?100000)，op( 1?\leq?op?\leq?3)$.

The next line contains $n$ numbers: $a_1, a_2 ,… , a_n (1?\leq?a_i?\leq?1000000)$.

# Standard Output

-For the $i$-th test case , first output Case #i: in a single line.

Then output the answer of $i$-th test case.

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
<tr><td>3
2 1
4 2
2 2
4 2
2 3
4 2</td><td>Case #1: 0
Case #2: 6
Case #3: 6</td></tr></table>


# Constraints



# Note



# Source


