
# Content

A special day is the day that is $x^{th}$ day in that month, and happens to be $x^{th}$ day in that week.

In `February` $1^{st}$ in $2016$, this day in that month happens to be the first day in that week, so we call it a special day.

Now, given a time interval, how many special days in total?

# Standard Input

The first line is an integer $T(T \le 55)$, denoting the number of test cases.

Then $T$ lines follows, each test case one line.

Each line contains two dates $A$ and $B$, following such format: `year month day`.

$year \le 10^9$, $month$ and $day$ will be legal.

$A$ and $B$ will all be later than $2016/1/31$, and $B$ will not be earlier than $A$.

# Standard Output

For each query, output the answer in one line.

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
2016 2 1 2016 2 7
2016 2 1 2022 6 1</td><td>7
77</td></tr></table>


# Constraints



# Note

Note that the answer may be large, please using `long long`

# Source


