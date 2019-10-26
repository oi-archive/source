
# Content

A pair of integers ($a$,$b$) is called an amicable pair if the sum of the proper divisors of a equals b, and vice versa. For example, ($220$, $284$) is an amicable pair, since the proper divisors of $220$ are $1$, $2$, $4$, $5$, $10$, $11$, $20$, $22$, $44$, $55$ and $110$, and $1$ `+` $2$ `+` $4$ `+` $5$ `+` $10$ `+` $11$ `+` $20$ `+` $22$ `+` $44$ `+` $55$ `+` $110 = 284$, while the proper divisors of $284$ are $1$, $2$, $4$, $71$ and $142$ and their sum is $220$. 

Given $K$, output the number of different amicable pairs ($a,b$) where $1 \leq a \leq K$ and $1 \leq b \leq K$. Note that ($a,b$) is considered the same pair as ($b,a$).

* Integer $a$ is a proper divisor of $b$ if $0 < a < b$ and there exists some integer $k$ such that $a$ `*` $k = b$.

# Standard Input

The first line is an integer T, number of test cases. T lines follow, each contains an integer K.
* $1 \leq T \leq 1000$
* $1 \leq K \leq 100000$

# Standard Output

For each case, output on a line the number of different amicable pairs satisfying the constraint above.

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
220
284</td><td>2
3</td></tr></table>


# Constraints



# Note



# Source


