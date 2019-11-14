
# Content

A number is said to be made up of non-decreasing digits if all the digits to the left of any digit is less than or equal to that digit. For example, the four-digit number `1234` is composed of digits that are non-decreasing. Some other four-digit numbers that are composed of non-decreasing digits are `0011`, `1111`, `1112`, `1122`, `2223`. As it turns out, there are exactly `715` four-digit numbers composed of non-decreasing digits.

Notice that leading zeroes are required: `0000`, `0001`, `0002` are all valid four-digit numbers with nondecreasing digits. 

For this problem, you will write a program that determines how many such numbers there are with a specified number of digits.

# Standard Input

The first line of input contains a single integer $P$, ($1\leq P\leq 1000$), which is the number of data sets that follow. Each data set is a single line that contains the data set number, followed by a space, followed by a decimal integer giving the number of digits $N$, ($1\leq N\leq 64$).

# Standard Output

For each data set there is one line of output. It contains the data set number followed by a single space, followed by the number of $N$ digit values that are composed entirely of non-decreasing digits.

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
1 2
2 3
3 4</td><td>1 55
2 220
3 715</td></tr></table>


# Constraints



# Note



# Source


