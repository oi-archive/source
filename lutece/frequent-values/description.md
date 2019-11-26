
# Content

You are given a sequence of $n$ integers $a\_1, a\_2,\cdots , a\_n$ in non-decreasing order. In addition to that, you are given several queries consisting of indices $i$ and $j$ ($1\leq i\leq j\leq n$). For each query, determine the most frequent value among the integers $a\_i ,\cdots , a\_j$.

# Standard Input

The input consists of several test cases. Each test case starts with a line containing two integers $n$ and $q$ ($1\leq n, q\leq 100000$). The next line contains $n$ integers $a\_1 , \cdots , a\_n$ ($-100000\leq a\_i\leq 100000$, for each $i\in [1, \cdots, n]$) separated by spaces. You can assume that for each $i \in [1, \cdots, n-1]: a\_i \leq a\_{i+1}$. The following $q$ lines contain one query each, consisting of two integers $i$ and $j$ ($1\leq i\leq j\leq n$), which indicate the boundary indices for the 
query.

The last test case is followed by a line containing a single $0$.

# Standard Output

For each query, print one line with one integer: The number of occurrences of the most frequent value within the given range.

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
<tr><td>10 3
-1 -1 1 1 1 1 3 10 10 10
2 3
1 10
5 10
0</td><td>1
4
3</td></tr></table>


# Constraints



# Note



# Source


