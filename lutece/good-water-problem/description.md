
# Content

Given $n$ integers, you are allowed to change the numbers in a sequence of steps.

In each step, you can:

Select two numbers $x$ and $y$.

Erase $x$ and $y$.

Write two new integers onto the blackboard: $gcd(x, y)$ and $lcm(x, y)$.

(Above, $gcd(x,y)$ denotes the greatest common divisor and $lcm(x,y)$ the least common multiple of $x$ and $y$.)

Your goal is to maximize the maximum number. Under that circumstance, try to maximize the second largest number, the third largest number, and so on.

# Standard Input

The first line contains an integer $T$, denoting the number of the test cases.

$T \le 5$

For each case, there is an integer $n$. $(n \le 10^5)$

The next line contains $n$ integers. Let $a_i$ denotes the $i^{th}$ number. $(a_i \le 10^6)$

# Standard Output

Output $n$ numbers, the answer mod $10^9+7$, denoting the largest number, the second largest number, and so on.

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
4
999983 999983 999979 32
</td><td>783787438 999983 1 1</td></tr></table>


# Constraints



# Note



# Source


