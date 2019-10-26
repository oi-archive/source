
# Content

Given $N$ unsigned $64$-bit integers, you can `bitwise NOT` each or not. Then you need to add operations selected from `bitwise XOR`, `bitwise OR` and `bitwise AND`, between any two successive integers and calculate the result. Your job is to make the result as small as possible.

# Standard Input

The first line of the input is $T$ (no more than $1000$), which stands for the number of test cases you need to solve.

Then $T$ blocks follow. The first line of each block contains a single number $N$ ($1 \leq N \leq 100$) indicating the number of unsigned $64$-bit integers. Then $n$ integers follow in the next line.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and counts from $1$. Then output the answer.

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
3
1 2 3
2
3 6</td><td>Case #1: 0
Case #2: 1</td></tr></table>


# Constraints



# Note

* Case #$1$: `1|2^3 = 0`
* Case #$2$: `3&(~6) = 1`

The `bitwise NOT`, is a unary operation that performs logical negation on each bit, forming the ones' complement of the given binary value. Digits which were $0$ become $1$, and vice versa.

The `bitwise OR` takes two bit patterns of equal length, and produces another one of the same length by matching up corresponding bits (the first of each; the second of each; and so on) and performing the logical inclusive or operation on each pair of corresponding bits. In each pair, the result is $1$ if the first bit is $1$ or the second bit is $1$ or both bits are $1$; otherwise, the result is $0$.

The `bitwise XOR` takes two bit patterns of equal length and performs the `logical XOR` operation on each pair of corresponding bits. The result in each position is $1$ if the two bits are different, and $0$ if they are the same.

# Source


