
# Content

Given a text $s[1\cdots n]$ of length $n$, we create its **suffix array** by taking all its suffixes: $s[1\cdots n], s[2\cdots n],\cdots, s[n\cdots n]$ and sorting them lexicographically. As a result we get a sorted list of suffixes: $s[p\_1\cdots n], s[p\_2\cdots n],\cdots , s[p\_n\cdots n]$ and call the sequence $p\_1,p\_2,\cdots ,p\_n$ the suffix array of $s[1\cdots n]$.

For example, if $s =$ `abbaabab`, the sorted list of all suffixes becomes: `aabab`, `ab`, `abab`, `abbaabab`, `b`, `baabab`, `bab`, `bbaabab` and the suffix array is $4$, $7$, $5$, $1$, $8$, $3$, $6$, $2$.

It turns out that it is possilble to construct this array in linear time. Your task will be completely different, though: given $p\_1, p\_2, p\_3\cdots p\_n$, you should tell me how many possible sequences lead to this suffix array using at most m different letters.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 10$), which stands for the number of test cases you need to solve.

Every test case begins with $2$ integer $n$, $m$($1\leq n, m\leq 100000$) indicating the length of the sequence and the letters you can use. Then the next line contains n different numbers from $1$ to n which form a permutation indicating the suffix array.

# Standard Output

For every test case, you should output `Case #k: ` first, where k indicates the case number and starts at $1$. Then output an integer indicating the answer to this text case. As the answer may be very large, you only need to output the remainder when it divides $1000003$ which is a prime.

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

1 26
1

2 26
2 1</td><td>Case #1: 26
Case #2: 351</td></tr></table>


# Constraints



# Note



# Source


