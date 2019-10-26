
# Content

Suffix number i of a string $S$ is the suffix that starts with the character $S\_i$. For example, for $S=$`abcde` suffix $0$ is `abcde` and suffix $3$ is `de`. 

The suffix array of a string $S$ is defined as the permutation of suffix numbers that corresponds to their lexicographic order. For example, suppose that $S=$`abca`. If we order all suffixes of $S$ lexicographically, we get the following: `a` < `abca` < `bca` < `ca`. The corresponding suffix numbers are $3$, $0$, $1$, and $2$, in this order. Thus, for this string S the suffix array would be ${3, 0, 1, 2}$. Note that the length of a suffix array is the same as the length of the original string. 

Now Alice is given an array $A$: the suffix array of an unknown string. She is wondering how many possible strings satisfying this array if the size of charset is $m$. 

As is known to everyone of you, Bob loves Alice very much. Could you tell Bob the answer to help Bob leave a good impression on Alice.

# Standard Input

The first line contains $2$ integers $n$ and $m$, indicating the length of the suffix array and the size of charset.

The next line contains $n$ integers $A\_i$, indicating the element in the suffix array.

It is guaranteed that the suffix array is a permutation of $[0, n - 1]$, and $1 \leq n, m \leq 2000000$

# Standard Output

Print the answer module 1000000007 in one line.

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
<tr><td>3 2
0 2 1</td><td>1</td></tr></table>


# Constraints



# Note



# Source


