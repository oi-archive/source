
# Content

Charlie are given a binary string of length $N$ ( $1 \leq N \leq 2 \cdot 10^5$ ).

Now Charlie wants to cut some character so that's easy to carry.

For every step, Charlie arbitrarily find one substring `01` to delete it until not exist such substring.

Charlie wants to know the expectation of the length after cutting.

# Standard Input

The first line is an integer $T$($1 \leq T \leq 68$), which indicates the number of testcases.

For each testcase:

The first line of the input file contains the integer $N$.

The second line contains the binary string $s$ of length $N$, consisting of letters `0` and `1` only.

# Standard Output

For each testcase, your program should output the expectation of the length of the remain string. The answer should keep three decimal digits.

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
4
1101</td><td>2.000</td></tr><tr><td>1
6
010101
</td><td>0.000</td></tr></table>


# Constraints



# Note



# Source


