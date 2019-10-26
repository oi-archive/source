
# Content

There is a sequence of brackets, which supports two kinds of operations.
1. we can choose a interval $[l,r]$, and set all the elements range in this interval to left bracket or right bracket. 
2. we can reverse a interval, which means that for all the elements range in $[l,r]$, if it's left bracket at that time, we change it into right bracket, vice versa.

Fish is fond of `Regular Bracket Sequence`, so he want to know whether a interval $[l,r]$ of the sequence is regular or not after doing some operations.

Let us define a regular brackets sequence in the following way: 
1. Empty sequence is a regular sequence. 
2. If `S` is a regular sequence, then `(S)` is also a regular sequences. 
3. If `A` and `B` are regular sequences, then `AB` is a regular sequence.

# Standard Input

In the first line there is an integer $T$ ($T\leq 10$), indicates the number of test cases. Each case begins with a line containing an integers $N$ ($N \leq 100,000$ and $N$ is a even number), the size of the initial brackets sequence. The next line contains a string whose length is $N$ consisting of `(` and `)`. In the third of each test case, there is an integer $M$($M \leq 100,000$) indicates the number of queries. Each of the following $M$ lines contains one operation as mentioned below. The index of the bracket sequence is labeled from $0$ to $N - 1$.

Three operation description:
* `set l r c`: change all the elements range in $[l,r]$ into `(` or `)`.($c$ is `(` or `)`)
* `reverse l r`: reverse the interval $[l,r]$
* `query l,r`: you should answer that interval $[l,r]$ is regular or not

# Standard Output

For each test case, print a line containing the test case number (beginning with $1$) on its own line, then the answer for each `query` operation, if the interval is regular, print `YES`, otherwise print `NO`, one on each line.

Print a blank line after each test case.

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
((()))
8
query 0 5
set 0 5 (
query 0 5
reverse 3 5
query 0 5
query 1 4
query 2 3
query 0 4</td><td>Case 1:
YES
NO
YES
YES
YES
NO</td></tr></table>


# Constraints



# Note

Huge input, use `scanf` instead of `cin`.

# Source


