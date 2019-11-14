
# Content

There are some piles of apples in a line from left to right and every pile has a fixed number of apples. If you choose a pile to pick, you have to pick all the apples of this pile. You want to pick a consecution of piles out and then add them together to share them with your friends. But your friends are very petty. For every one of your friends, he won't be happy if you give more apples of another friends than him. How many ways do you have to pick piles to make all of them stay happy? (And you can't divide any single apple into two or more pieces, of course.)

# Standard Input

The first line contains an integer $T$($1\leq T\leq 10$) indicating the number of test cases. The first line of each test case contains two integers $N$($1\leq N\leq 100000$) and $M$ ($1\leq M\leq 100000$) indicating the number of piles and the number of your friends. The following line contains $N$ positive integers indicate the number of apples in each pile from left to right. The number of apples in each pile is no more than $1000000000$.

# Standard Output

For each test case, just output one line.

First output `Case #C: `,where $C$ is number of test case which is from $1$ to $T$.Then,output the the number of ways you can pick piles.

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
3 4
1 3 4
4 9
2 4 6 8</td><td>Case #1: 3
Case #2: 1</td></tr></table>


# Constraints



# Note

The answer will be very large, but it will be fit in 64-bit integer. So, please use `long long`.

# Source


