
# Content

In the Qingshuihe Campus of UESTC, the most annoy problem to students are the flagstone path on the lawn. The designer seems so stupid that the flagstone path often make students step in the gap. Now a perfect step is wanted in order to not step in any gaps and step on every flagstone. The step length is required to be constant while the length of the flagstone and gap are given different. The problem is asking you to tell the minimum length of the perfect step. To simplify the question, the foot is considered to be a point and the very beginning is the fore edge of the first flagstone, which also means the first flagstone has already been stepped on.

# Standard Input

The first line of the input contains one integer $T$, which indicate the number of test cases. In each test case, the first line contains an integer $N$($2 \leq N \leq 10^5$), indicating the number of flagstone. Following $N$ lines, and each line is the length of one flagstone. And the following $N-1$ lines are the length of the gaps. All data is integer. All the length will be a positive integer, and the sum of them will fit in a `32bit` signed integer.

# Standard Output

One line for each test case contains only one number indicating the answer. One real number indicating the perfect step length should be accurate to two digits after the radix point. If it is impossible to find out a perfect step, just output `impossible` !

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
2
10
20
5
3
10
20
5
5
1000</td><td>15.00
impossible</td></tr></table>


# Constraints



# Note

每个石板踏且仅踏一次

# Source


