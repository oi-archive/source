
# Content

Give a sequence of $N$ integers, you are required to deal with the following operations.
1. For each integer in the interval $[L, R]$, change its value to previous value multiplying or dividing an integer $x$.
2. Output the remainder of the product of all the integers in interval $[L, R]$ mod a particular modulus.

# Standard Input

First line of the input is a single integer $T$($1\leq T\leq 15$), indicating there are $T$ test cases.

The first line of each test case contains two numbers $N$ $(1 \leq N \leq 10^4)$ and M $(1 \leq M \leq 10^9)$.

The second line contains $N$ numbers, the initial values of $A_1, A2, \cdots , A_N$. $0 \leq A_i \leq 10^9$.

The third line contains a single number $Q$.

Each of the next $Q$ lines represents an operation.

* `M L R x` means for each integer in the interval $[L, R]$, changing its value to previous value multiplying an integer $x$,
we guarantee that $x$ is not exceeded $10^9$ and non negative.
* `D L R x` means for each integer in the interval $[L, R]$, changing its value to previous value dividing an integer $x$,
we guarantee that $x$ is positive integer not exceeded $10^9$ and all the integers in the interval $[L, R]$ can be divided into x parts with no remainder.
* `Q L R` means output the remainder of the product of the integer in interval $[L, R]$ mod $M$.

For all the operations, we guarantee that $L \leq R$ and there is a blank line before each test case.

# Standard Output

For each test case, print `Case #t:` first, in which $t$ is the number of the test case starting from $1$.

Then for each `Q L R` operation, output a single num in each line as the input says.

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

5 6
10 2 6 9 10
5
Q 1 2
M 1 4 3
Q 1 5
D 1 3 2
Q 1 3
</td><td>Case #1:
2
0
3</td></tr></table>


# Constraints



# Note



# Source


