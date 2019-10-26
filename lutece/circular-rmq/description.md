
# Content

You are given circular array $a\_0, a\_1, \cdots , a\_{n - 1}$. There are two types of operations with it:
1. `inc(lf, rg, v)` — this operation increases each element on the segment $[lf, rg]$ (inclusively) by $v$;
2. `rmq(lf, rg)` — this operation returns minimal value on the segment $[lf, rg]$ (inclusively).

Assume segments to be circular, so if $n = 5$ and $lf = 3, rg = 1$, it means the index sequence: `3, 4, 0, 1`.

Write program to process given sequence of operations.

# Standard Input

The first line contains integer $n$ ($1\leq  n \leq  200000$). The next line contains initial state of the array: $a\_0, a\_1, \cdots , a\_{n - 1}$ ( $- 10^6 \leq  a\_i \leq 10^6$), $a\_i$ are integer. The third line contains integer $m$ ($0 \leq  m \leq  200000$), $m$ — the number of operartons. Next $m$ lines contain one operation each. If line contains two integer $lf, rg$ ($0 \leq  lf, rg \leq  n - 1$) it means `rmq` operation, it contains three integers $lf, rg, v$ ($0 \leq  lf, rg \leq  n - 1$, $ - 10^6 \leq  v\leq 10^6$) — `inc` operation.

# Standard Output

For each `rmq` operation write result for it.

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
<tr><td>4
1 2 3 4
4
3 0
3 0 -1
0 1
2 1</td><td>1
0
0</td></tr></table>


# Constraints



# Note



# Source


