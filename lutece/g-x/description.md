
# Content

For a binary number $x$ with $n$ digits ($A\_{n}A\_{n-1}A\_{n-2}\cdots A\_{2}A\_{1}$), we encode it as
$G(x) = x\otimes \lfloor\frac{x}{2}\rfloor$. Where $\otimes $ is bitwise XOR operation
and $\lfloor x\rfloor $ indicates the largest integer which is not greater than $x$.

Due to some reasons, Mzry1992 encode his password $P$ into $G(P)$, and additionally, 
he encode $P + 1$ into $G(P + 1)$ too, and write $G(P)$ and $G(P + 1)$ into his diary.

This story happened many years ago and now you hold the diary with these numbers 
in your hands. Unfortunately, some digits are unreadable now. Could you determine the
values of these digits using the readable digits?

# Standard Input

The first line has a number $T$ ($T\leq 100$) , indicating the number of test cases.

For every test case, it has $2$ lines of same number of digits describe $G(P)$ and $G(P + 1)$,
In every line, it only contains `1`, `0` and `?`. Unreadable digits are denoted with symbol `?`,
The length of every line in the input is up to $10^5$.

# Standard Output

For every case, you should output `Case #t: ` at first, without quotes. The $t$ is the case number starting from $1$.

Then, if there is impossible to restore $G(P)$ and $G(P + 1)$, you should output `Impossible`
in the second line. 

Otherwise, if $G(P)$ is unique, you should output restored $G(P)$ and $G(P + 1)$ in the same format.

Otherwise, you should output `Ambiguous` and the number of possible $G(P)$ in the second line.

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
10??
10??
0010
0110
1?01
0?01</td><td>Case #1:
Ambiguous 3
Case #2:
0010
0110
Case #3:
Impossible</td></tr></table>


# Constraints



# Note

In the first sample case, the three possible situations are:

* $1010$<br/>$1011$
* $1011$<br/>$1001$
* $1001$<br/>$1000$

# Source


