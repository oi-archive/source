
# Content

You have $N$ integers, $A\_1, A\_2, \cdots , A\_N$. You need to deal with two kinds of operations. One type of operation is to add some given number to each number in a given interval. The other is to ask for the sum of numbers in a given interval.

# Standard Input

There is only one testcase.

The first line contains two numbers $N$ and $Q$. $1\leq N,Q\leq 100000$.

The second line contains $N$ numbers, the initial values of $A\_1, A\_2,\cdots , A\_N$. $-1000000000\leq A\_i\leq 1000000000$.

Each of the next $Q$ lines represents an operation.
* `C a b c` means adding $c$ to each of $A\_a, A\_{a+1}, \cdots , A\_b$. $-10000\leq c\leq 10000$.
* `Q a b` means querying the sum of $A\_a, A\_{a+1},\cdots , A\_b$.

# Standard Output

You need to answer all $Q$ commands in order. One answer in a line.

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
<tr><td>10 5
1 2 3 4 5 6 7 8 9 10
Q 4 4
Q 1 10
Q 2 4
C 3 6 3
Q 2 4</td><td>4
55
9
15</td></tr></table>


# Constraints



# Note

The sums may exceed the range of $32$-bit integers.

The data used in this problem is unofficial data prepared by standy. So any mistake here does not imply mistake in the offcial judge data.

# Source


