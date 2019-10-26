
# Content

An equal sum partition of a sequence of numbers is a grouping of the numbers (in the same order as the original sequence) in such a way that each group has the same sum. For example, the sequence:`2 5 1 3 3 7`

may be grouped as:`(2 5) (1 3 3) (7)`

to yield an equal sum of $7$.

Note: The partition that puts all the numbers in a single group is an equal sum partition with the sum equal to the sum of all the numbers in the sequence.

For this problem, you will write a program that takes as input a sequence of positive integers and returns the smallest sum for an equal sum partition of the sequence.

# Standard Input

The first line of input contains a single integer $P$, ($1\leq P\leq 1000$), which is the number of data sets that follow. The first line of each data set contains the data set number, followed by a space, followed by a decimal integer $M$, ($1\leq M\leq 10000$), giving the total number of integers in the sequence. The remaining line(s) in the dataset consist of the values, $10$ per line, separated by a single space. The last line in the dataset may contain less than $10$ values.

# Standard Output

For each data set, generate one line of output with the following values: The data set number as a decimal integer, a space, and the smallest sum for an equal sum partition of the sequence.

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
1 6
2 5 1 3 3 7
2 6
1 2 3 4 5 6
3 20
1 1 2 1 1 2 1 1 2 1
1 2 1 1 2 1 1 2 1 1</td><td>1 7
2 21
3 2</td></tr></table>


# Constraints



# Note



# Source


