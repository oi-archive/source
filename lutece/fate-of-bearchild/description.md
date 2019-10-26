
# Content

Bearchild is born for Math, bearchild is born for numbers. Numbers are faith, numbers are justice, numbers are power, numbers are the way to talk to God.

Bearchild finds permutations fascinating, he immediately writes $n$ numbers, from $1$ to $n$, on a paper. Then he begins to play with the number sequence.

Bearchild can change a sequence to a new one. This is how he does: he chooses a number from the second one to the last one in the sequence, and swaps it with the first number. So there are $n-1$ ways to change a sequence into another.

At first, there is only one sequence written by bearchild on the paper. Then he changes the sequence into another one in $n-1$ ways, and writes all of them down. So there are $n$ sequences on the paper in total after the first step.

Then he repeat this process, he change all the n sequences, each with $n-1$ new sequences, so there will be $n^2$ sequences in total, after the second step.You can see, after the $q_{th}$ step, there will be $n^q$ sequences on the paper. Some of them might be the same, but it doesn’t matter.

Bearchild wonders the sum of the number of inversion pairs in each sequence on the paper. Here a `inversion pair` means a pair $<i,j>$  with $i<j$ and $A\_i>A\_j$, in the sequence $A$. ($0\leq i, j<n$)

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 10000$) . For each case, there is two numbers $n$ and $q$, as described in the sequence. ($1\leq n,q\leq 1,000,000,000$).

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output the answer, mod $1000000007$.

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
3 1
3 2
4 2</td><td>Case #1: 4
Case #2: 12
Case #3: 38</td></tr></table>


# Constraints



# Note

For the first sample, the original sequence is `1 2 3`, after $1$ step, there will be $3$ sequences on the paper, they are `1 2 3`, `2 1 3` and `3 2 1`, each has a number of inversion pairs $0$, $1$ and $3$, so the answer is $0+1+3=4$.

# Source


