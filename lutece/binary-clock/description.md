
# Content

A binary clock is a clock which displays traditional sexagesimal time (military format) in a binary format. The most common binary clock uses three columns or three rows of LEDs to represent zeros and ones. Each column (or row) represents a time-unit value.

When three columns are used (vertically), the bottom row in each column represents $1$ (or $20$ ), with each row above representing higher powers of two, up to $25$ (or $32$). To read each individual unit (hours, minutes or seconds) in the time, the user adds the values that each illuminated LED represents, and then reads the time from left to right. The first column represents the hour, the next column represents the minute, and the last column represents the second.

When three rows are used (horizontally), the right column in each row represents $1$ (or $20$ ), with each column left representing higher powers of two, up to $25$ (or $32$). To read each individual unit (hours, minutes or seconds) in the time, the user adds the values that each illuminated LED represents, and then reads the time from top to bottom. The top row represents the hour, the next row represents the minute, and the bottom row represents the second.

For example:

![title](/source/lutece/binary-clock/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzQ1LzIwMTQwNDEwMjEzNTQxMzA0MjEucG5n.png)

For this problem you will read a time in sexagesimal time format, and output both the vertical and e horizontal binary clock values. The output will be formed by concatenating together the bits in each column (or row) to form two $18$ character strings of `1`'s and `0`'s as shown below.

For example, `10:37:49` would be written vertically as `011001100010100011` and horizontally as `001010100101110001`.

# Standard Input

The first line of input contains a single integer $N$,($1\leq N\leq 1000$) which is the number of data sets that follow. Each data set consists of a single line of input containing the time in sexagesimal format.

# Standard Output

For each data set, you should generate one line of output with the following values: The data set number as a decimal integer (start counting at one), a space, the binary time in vertical format ($18$ binary digits), a space and the binary time in horizontal format ($18$ binary digits).

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
10:37:49 
00:00:01</td><td>1 011001100010100011 001010100101110001 
2 000000000000000001 000000000000000001</td></tr></table>


# Constraints



# Note



# Source


