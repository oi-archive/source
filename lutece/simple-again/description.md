
# Content

Suppose you have n days to do something with your ability.
The initial value of your ability is zero.

Every single day(suppose the $i\_th$ day) you can do only one of
the following things:
1. Improve yourself. So the value of your ability will increase $a\_i$.
2. Use the current value of your ability to get the same 
amounts of money.

For example, you have the ability as $V$, so this day you can get money $V$. 
However, you cannot improve your ability this day.

Can you program to figure out:
in these $n$ days, how much money can you get at most?

# Standard Input

the first line is an integer $T$ which stands for the number of test cases.
For each test case, the first line gives you $n$($1\leq n\leq 100000$),
which means you have $n$ days totally. The following line consists
of $n$ integer(s), all of these represent the array $a$($0\leq a\_i\leq 10^6$),
as we mentioned above.

You know, with your ages growing, the ability you can improve 
everyday is shrinking. So that for each $i < n$ we have $a\_i \geq a\_{i+1}$.

# Standard Output

For each test cases, output the number of money you can get at most.

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
<tr><td>1
3
6 5 5</td><td>12</td></tr></table>


# Constraints



# Note



# Source


