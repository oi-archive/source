
# Content

When sorted in standard order, strings with digits in them may not sort to where they are expected. For instance, xyz100 precedes xyz2. In some applications such as listing files, normal order sort may be used where any string of digits in a character string is treated as a single digit with numerical value given by the digit string. For example, the following are in normal order:

`XYZ001`, `XYZ2`, `XYZ003`, `XYZ08`, `XYZ23`, `XYZ100`, `XYZQ`

We wish to extend normal order sort in two ways:
1. Lower case and upper case letters sort the same (with the upper case value).
2. If a plus (+) or minus (-) sign precedes a digit and does not follow a digit, it is considered part of the following number for sorting purposes.

So `123+456+7890` are three numbers separated by plus signs but `A+003` is the same as `A3`.

To do our sort, we will use a library sort routine but we need to furnish a comparison routine. Write a comparison routine which takes as input two strings of printable, non-space ASCII characters ($\rm chr(33)-\rm chr(126)$) and returns:
* `-1` if the first string should precede the second in extended normal order
* `0` it the two strings are the same in extended normal order, or
* `1` if the first string should follow the second in extended normal order.

# Standard Input

The first line of input contains a single integer $N$ , ($1\leq N\leq 1000$) which is the number of data sets that follow. Each data set consists of a single line of input containing the two strings to be compared separated by a space. **The length of each string isn't larger than $100$.**

# Standard Output

For each data set, you should generate one line of output with the following values: The data set number as a decimal integer (start counting at one), a space and `-1`, `0` or `1` depending on whether the first string precedes, is the same as, or follows the second string in extended normal order.

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
<tr><td>5 
x-3 X0001 
123-456-7890 123+456+7890 
xYz000123J XyZ+123j 
#$%^&*[]- abcdefgh 
Abc47jKL+00123 ABC+47jkL123</td><td>1 -1 
2 1 
3 0 
4 -1 
5 0</td></tr></table>


# Constraints



# Note



# Source


