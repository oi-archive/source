
# Content

/* ----------------------------------------------------------------------------------

　　Given a two-dimensional array of positive and negative integers, a sub-rectangle is any contiguous sub-array of size $1 \times 1$ or greater located within the whole array. The sum of a rectangle is the sum of all the elements in that rectangle. In this problem the sub-rectangle with the largest sum is referred to as the maximal sub-rectangle.

As an example, the maximal sub-rectangle of the array:
```
0 -2 -7 0
9 2 -6 2
-4 1 -4 1
-1 8 0 -2
```
is in the lower left corner:
```
9 2
-4 1
-1 8
```
and has a sum of $15$.

---------------------------------------------------------------------------------- */

Your task here has something similar with the problem mentioned above, while you are to find out a non-empty sub-matrix whose elements sum closest to the given integer $T$.

# Standard Input

The input contains several test cases.

Each test case begins with three integers $n$ $m$ $T$, which means there are $n$ rows and $m$ columns in the matrix and our target $T$ as mentioned above. Then $n$ lines follows, each of which consists of $m$ non-negative integers bounded in $[0, 10000]$.

You can assume that $0 < n \leq 20, 0 < m \leq 2000, 0 \leq T < 2^{15}$

$n = 0$ and $m = 0$ means the end of the input, which should not be processed.

# Standard Output

For each test case, you are to output a line in the from of `Case #:`, `#` is the test case number indexed from $1$, and then another line with the sum of the sub-matrix you found, if there is a tie, you should output the smaller one.

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
<tr><td>3 3 0
1 1 1
1 1 1
1 1 1

3 3 0
1 1 1
1 1 1
1 1 0

3 3 10
2 2 4
5 2 0
0 0 0</td><td>Case 1:
1
Case 2:
0
Case 3:
11</td></tr></table>


# Constraints



# Note



# Source


