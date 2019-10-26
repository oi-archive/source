
# Content

As we all know, Sasami is a professional Otaku. This month, the most famous animation shop ANIMATE hosts a new promotion activity, and she participates.

There's a sequence $A$ with $N$ numbers in ANIMATE's promotion activity board, which is numbered $A\_0,A\_1,\cdots ,A\_{N−1}$. Player should figure out another non-decreasing sequence $B$ in $5$ seconds, which has $N+1$ numbers and satisfies that $B\_i+B\_{i+1}=A\_i$ for any $i$ ($0\leq i < N$). Note that the sequence $B$ is not unique. In fact,one distinct sequence would get one special prize. Two sequences are different if they have different elements on the same index.(e.g. $[1, 2, 4]$ differs from $[1, 2, 5]$).

Sasami can use the power to get one answer immediately(if it exists), but how could a power-holder get only one imperfect prize? Therefore, she wonder show many different sequences totally that exist to get all the prizes.

# Standard Input

The first line of the input is $T$($T\leq 10$), the number of test cases.

Each test case starts with one integer $N$ ($3\leq N\leq 100000$), which represents the length of sequence $A$.

The following line contains $N$ integers, indicating the sequence $A$.Each element of $A$ is less than $10^9$.

# Standard Output

For each test case, you should output the answer in one line.

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
1 9 16</td><td>4</td></tr></table>


# Constraints



# Note

All the valid non-decreasing sequences are as follows:
1. `-2 3 6 10`
2. `0 1 8 8`
3. `-1 2 7 9`
4. `-3 4 5 11`

# Source


