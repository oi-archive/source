
# Content

KKX likes to play with sequences and find interesting things. For an integer sequence $A\_1, A\_2, \cdots , A\_N$, he subtracts every adjacent two elements to get another sequence of length $N-1$, $B\_1, B\_2, \cdots, B\_{N-1}$, where $B\_i = A\_i – A\_{i+1}$, $i = 1, 2, \cdots, N-1$. Keep on this method until only one element left. Obviously, for a sequence this number is unique.

KKX wants to know if he can rearrange the elements in the initial sequence $A$ in any order, what is maximal number left using the method above?

**Please use $64$-bit integers(`long long` in `C/C++`) to do calculation in this problem. And use the `%lld` specificator to read or write $64$-bit integers in `C/C++`.**

# Standard Input

There will be multiple test cases. The first line of the input is an integer $T$ ($T \leq 100$) indicating the number of test cases.

For each test case an integer $N$ ($1 \leq N \leq 50$) comes first indicating the number of elements in the initial sequence $A$. The next line contains $N$ integers with absolute value within $1000$.

# Standard Output

Print `Case #k: x` in a single line for each test case, in which $k$ represents the case number which starts from $1$, and $x$ is the maximal number left.

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
1 1 -1
5
2 1 5 -4 2</td><td>Case #1: 4
Case #2: 46</td></tr></table>


# Constraints



# Note



# Source


