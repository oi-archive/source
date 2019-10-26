
# Content

For this problem, you will write a program that reads in a sequence of $32$-bit signed integers. After each odd-indexed value is read, output the median (middle value) of the elements received so far.

# Standard Input

The first line of input contains a single integer $P$, ($1\leq P\leq 1000$), which is the number of data sets that follow. The first line of each data set contains the data set number, followed by a space, followed by an odd decimal integer $M$, ($1\leq M\leq 9999$), giving the total number of signed integers to be processed.

The remaining line(s) in the dataset consists of the values, $10$ per line, separated by a single space.

The last line in the dataset may contain less than $10$ values.

# Standard Output

For each data set the first line of output contains the data set number, a single space and the number of medians output (which should be one-half the number of input values plus one). The output medians will be on the following lines, $10$ per line separated by a single space. The last line may have less than $10$ elements, but at least $1$ element. There should be no blank lines in the output.

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
1 9
1 2 3 4 5 6 7 8 9
2 9
9 8 7 6 5 4 3 2 1
3 23
23 41 13 22 -3 24 -31 -11 -8 -7
3 5 103 211 -311 -45 -67 -73 -81 -99
-33 24 56</td><td>1 5
1 2 3 4 5
2 5
9 8 7 6 5
3 12
23 23 22 22 13 3 5 5 3 -3
-7 -3</td></tr></table>


# Constraints



# Note



# Source


