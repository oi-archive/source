
# Content

Bob has a sequence of $N$ integers. They are so attractive, that Alice begs to have a continued part of it(a continued part here also means a continued subsequence). However, Bob only allows Alice to chose it randomly. Can you give the expectation of the result of the bitwise `AND`, `OR`, `XOR` of all the chosen numbers?

# Standard Input

First line of the input is a single integer $T$($1 \leq T \leq 50$), indicating there are $T$ test cases.

The first line of each test case contains a single number $N$($1 \leq N \leq 50000$).

The second line contains $N$ integers, indicating the sequence.

All the $N$ integers are fit in $[0, 10^9]$.

# Standard Output

For each test case, print `Case #t: a b c` , in which t is the number of the test case starting from $1$, $a$ is the expectation of the bitwise `AND`, $b$ is the expectation of `OR` and $c$ is the expectation of `XOR`.

Round the answer to the sixth digit after the decimal point.

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
2
1 2
3
1 2 3
3
2 3 4</td><td>Case #1: 1.000000 2.000000 2.000000
Case #2: 1.333333 2.500000 1.666667
Case #3: 1.833333 4.333333 3.666667</td></tr></table>


# Constraints



# Note

`AND` is a binary operation, performed on two numbers in binary notation. First, the shorter number is prepended with leading zeroes until both numbers have the same number of digits (in binary). Then, the result is calculated as follows: for each bit where the numbers are both $1$ the result has $1$ in its binary representation. It has $0$ in all other positions.

`OR` is a binary operation, performed on two numbers in binary notation. First, the shorter number is prepended with leading zeroes until both numbers have the same number of digits (in binary). Then, the result is calculated as follows: for each bit where the numbers are both $0$ the result has $0$ in its binary representation. It has $1$ in all other positions.

`XOR` is a binary operation, performed on two numbers in binary notation. First, the shorter number is prepended with leading zeroes until both numbers have the same number of digits (in binary). Then, the result is calculated as follows: for each bit where the numbers differ the result has $1$ in its binary representation. It has $0$ in all other positions.

# Source


