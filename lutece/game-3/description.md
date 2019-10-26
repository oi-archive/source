
# Content

Standy is playing a cut-sequence game. It gives a sequence of $N$ numbers $a\_1, a\_2, \cdots a\_N$. Standy can remove at most two consecutive fragments. Then he computes the length of the longest consecutive increasing subsequence. What is the maximum possible length he can get?

# Standard Input

The first line of the input is an integer $T$ ($T\leq 10$), which stands for the number of test cases you need to solve.

Each test case begins with an integer $N$ ($1\leq N\leq 10^5$) indicating the size of the sequence. 

The next line contains $N$ integers $a\_1, a\_2, \cdots , a\_N$ ($0\leq a\_i\leq 10^9, 1\leq i\leq N$).

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then output the maximum possible length of consecutive increasing subsequence after remove at most two consecutive fragments.

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
4
1 2 3 4
12
10 1 2 7 9 3 4 8 8 5 6 1</td><td>Case #1: 4
Case #2: 6</td></tr></table>


# Constraints



# Note

For the $2\_{nd}$ Case, we can remove $2$ fragments `7 9` and `8 8`, and get sequence `10 1 2 3 4 5 6 1`. So the longest subsequence is `1 2 3 4 5 6`.

# Source


