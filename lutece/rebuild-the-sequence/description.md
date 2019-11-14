
# Content

Because of the good management, Miss Xue’s kindergarten attracts a lot of children coming to attend it. She is happy to count the number of children in her kindergarten since it never decreases.

As you know, being with a lot of children means trouble. The most naughty one, Lily, poured her coffee onto Miss Xue’s chart which recording the sequence of the numbers of children in the kindergarten on each day. Some data on the chart could not be recognized now.

Poor Miss Xue comes to you for help. Given the data remaining available, in which the numbers of children on the first and last day are still remembered by Miss Xue, she wants to know how many ways to reconstruct the sequence.

What’s more, in order to obtain more information about the unknown original sequence, Miss Xue defined a function S for each potential reconstruction method. For a specific sequence $A$, function $S(A)$ equals the sum of all numbers in $A$. For example, $S(1,2,9,10,15) = 1+2+9+10+15 = 37$. Miss Xue thinks that the mean of function $S$ for all potential reconstruct methods may help her somewhat. 

Please tell her answers to the above two questions.

# Standard Input

First an integer $T$, indicates the number of test cases.

Every test case begins with three integers $N$, $M$. $N$ is the length of the original sequence, and $M$ represents numbers available. The following two lines give two list of $M$ numbers, $A[1\cdots M]$, $B[1\cdots M]$. The $i\_{th}$ number’s original location is $A\_i$, and its value is $B\_i$. It is guaranteed that $A$ and $B$ are non-decreasing. At the same time, the first one is located at 1 and the last one is located at $N$.

$T \leq 100$;

$2 \leq N \leq 1,000,000$;

$2 \leq M \leq 1,000$, $M \leq N$;

$1 = A\_1 < A\_2 < \cdots < A\_M = N$;

$0 \leq B\_1 \leq B\_2 \leq \cdots \leq B\_M \leq 1,000,000$.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and counts from $1$. Then output the number of ways to rebuild the sequence, modulo $1,000,000,009$, and their mean, rounded to three digits after the decimal point, in the format shown in sample output.

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
6 6
1 2 3 4 5 6
3 5 10 15 20 20
6 5
1 2 3 5 6
3 5 10 20 20</td><td>Case #1: 1 73.000
Case #2: 11 73.000</td></tr></table>


# Constraints



# Note



# Source


