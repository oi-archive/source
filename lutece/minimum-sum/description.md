
# Content

You are given $N$ positive integers, denoted as $x\_0, x\_1\cdots x\_{N-1}$. Then give you some intervals $[l, r]$. For each interval, you need to find a number $x$ to make $\sum_{i=l}^{r}|x-x\_i|$ as small as possible!

# Standard Input

The first line is an integer $T$ ($T\leq 10$), indicating the number of test cases. For each test case, an integer $N$ ($1\leq N\leq 100,000$) comes first. Then comes $N$ positive integers $x$ ($1\leq x\leq 1,000, 000,000$) in the next line. Finally, comes an integer $Q$ ($1\leq Q\leq 100,000$), indicting there are $Q$ queries. Each query consists of two integers $l$, $r$ ($0\leq l\leq r < N$), meaning the interval you should deal with.

# Standard Output

For the $k\_{th}$ test case, first output `Case #k:` in a separate line. Then output $Q$ lines, each line is the minimum value of $\sum_{i=l}^{r}|x-x\_i|$. Output a blank line after every test case.

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

5
3 6 2 2 4
2
1 4
0 2

2
7 7
2
0 1
1 1</td><td>Case #1:
6
4

Case #2:
0
0</td></tr></table>


# Constraints



# Note



# Source


