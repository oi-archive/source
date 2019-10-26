
# Content

Bitwise NOT is a kind of bit operator, we defined that as follow: for a binary base number $A$, let $B=NOT\ A$, then for each bit of $B$, we can get its value by check the digit of corresponding position in $A$ . And for each digit, $NOT\ 1 = 0$, $NOT\ 0 = 1$. Normally, we simply write this operator as $\sim$, for example, for $4$ bits number, $\sim 10=5$, $\sim 6=9$.

NOT is an amazing operator and this is a problem about NOT. Give you $N$ numbers with M bits, you can choose whether do NOT opration on each number, by doing this, you should minimize the difference between maximal number and the minimal number. Calculate the minimal difference.

# Standard Input

First line of the input is a single integer $T$($T\leq 30$), indicates there are $T$ test cases.

For each test case, the first line is two integers $n$($1\leq n\leq 100000$) and $m$($1\leq m\leq 60$), the number of numbers and the bits each number has. The second line contains $n$ integers in decimal base(each number is between $0$ and $2^m-1$).

# Standard Output

For each case, you should output `Case #k: ` first, where $k$ indicates the case number between $1$ and $T$. Then output the minimum difference.

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
2 2
1 2
2 2
1 3</td><td>Case #1: 0
Case #2: 1</td></tr></table>


# Constraints



# Note

1. For example, consider that $\sim 10$ with $6$ bits, that is $\sim 001010_2=110101_2$, so the result is $53$.
2. Huge input, `scanf` is recommended.

# Source


