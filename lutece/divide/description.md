
# Content

Alice and Bob has found a island of treasure in byteland! They find $N$ kinds of treasures on the island, and each kind of treasure has a certain number, and as in byteland, the value of each treasure will be a power of $2$, such as $1,2,4,8 \cdots$

Now the only problem is how to divide treasures fairly, they need to divide the treasures into two parts, and the value of each part is the sum of all treasures' in this part, they want to make the difference between the value of two parts as small as possible, can you help them?

# Standard Input

First line of the input is a single integer $T$($1 \leq T \leq 20$), indicating there are $T$ test cases.

For each test case, the first line contain one integer $N$($2 \leq N \leq 10^5$), indicate the different kinds of treasures.

Then $N$ line followed, each line will have follow two integer $a\_i$($0 \leq a\_i \leq 10^5$) and $x\_i$($0 \leq x\_i \leq 10^9$), indicate there are $x\_i$ $i\_{th}$ treasures, and the value of each one is $2^{a\_i}$.

# Standard Output

For each case, you should output a single line, first output `Case #t: `, where $t$ indicating the case number between $1$ and $T$, then a string with only `0` and `1` followed, indicate the minimum difference in binary representation, find more details in samples.

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
2
0 2
2 1
4
0 1
1 1
2 1
3 1
4
0 2
1 1
2 1
3 1</td><td>Case #1: 10
Case #2: 1
Case #3: 0</td></tr></table>


# Constraints



# Note



# Source


