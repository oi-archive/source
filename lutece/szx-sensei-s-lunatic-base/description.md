
# Content

Recently SZX sensei is addicted to encryption and wants to invent a new, strange and lunatic base. That is the every digit of a number is different! So given a key number of which the every digit indicates the base on every digit you can change the decimal number into the lunatic base and vice versa. For example the key number might be $268$ meaning that the base of first digit (from the right) is octal (八进制) and the second is senary (六进制) and the third is binary (二进制). See the sample to learn more.

|In base 2345|In decimal|
|:--:|:--:|
|1 | 1 |
|2|  2 |
|10|  5 |
|11|  6 |
|14| 9 |
|21 | 11 | 
|33|18 |

# Standard Input

The first line of the input is a single number $N$($N\leq 10,000$) indicating the number of test cases.The next $N$ lines might be either patten of the two `from x y` and `to x y`. $y$ is the key number of the encryption and every digit will be between $2$ and $9$. The former means you should change the decimal number $x$ into lunatic base y while the latter means you should change the number $x$ in lunatic base $y$ to a decimal number. The length of $x$ and $y$ are no more than $10$.

# Standard Output

For each test case, output one line. First ,output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then, output the number you've changed to.

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
<tr><td>4
from 11 2222
to 11 2222
from 11 2345
to 11 2345</td><td>Case #1: 1011
Case #2: 3
Case #3: 21
Case #4: 6</td></tr></table>


# Constraints



# Note



# Source


