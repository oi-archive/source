
# Content

Krolia define a new number which is called Kumber. To get a Kumber, one must do a Kumber Transformation on a positive integer which don't contains the digit $0$.

A Kumber Transformation is that delete a digit $i$($1\leq i\leq 9$) in the integer $a\_i$ times. For example, $a\_i=(1,1,1,0,0,0,0,0,0)$ and the integer $n=123321$, which means you must delete one digit $1$,one digit $2$ and one digit $3$ from $n$.After the Kumber Transformation you will get some Kumbers such as $123,321,231\cdots $

Given $a\_i$ and the positive integer $n$, you must find the largest Kumber which one can get from that Kumber Transformation.

# Standard Input

There is only one integer $T$($T\leq 100$) in the first line indicating the number of test cases.

The first line of each test cases contains an integer $n$($0\leq n<10^{101}$,No $0$-digit in number $n$), and the second line contains $9$ numbers $a\_i$ ($0\leq a\_i\leq 100$).We guarantee that the integer $n$ contains at least $a\_i$ digit $i$ and the sum of $a\_i$ is less than the length of n(that is to say, you won't get nothing after the transformation).

# Standard Output

For each test case, output an integer which is the largest Kumber you can get.

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
123321
1 1 1 0 0 0 0 0 0
212
0 1 0 0 0 0 0 0 0</td><td>321
21</td></tr></table>


# Constraints



# Note



# Source


