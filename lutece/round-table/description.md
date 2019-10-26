
# Content

I have $m$ little buddies, and tonight we will have a fancy dinner in my room.

Fortunately, I have a round table which is large enough for all my little buddies.
(As for me, I will not sit in the round table for some reasons)
And the round table is so large that I will not let my little buddies sit shoulder to shoulder.

That means I will select $m$ seats from $n$ seats, and there maximal length of 
consecutive seats in the original round table won't be larger than or equal to $k$. 
I want know how many different ways I can choose.

Here is one more thing, two ways are considered the same if and only if 
one can be obtained by rotation.

![title](/source/lutece/round-table/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODIwLzIwMTQwNDE3MTUzMjMxOTEwMS5qcGc=.jpg)

The answer may be very large so the answer should modulo $10^9+7$.

# Standard Input

The first line has a number $T$ ($T\leq 200$) , indicating the number of test cases.

Next each line contain three integer $n$, $m$, $k$ ($1\leq n\leq 10^5$, $1\leq m\leq 10^5$, $2\leq k\leq 10^5$, $m\leq n$).

# Standard Output

For every case, you should output `Case #t:` at first, without quotes. The $t$ is the case number starting from $1$.

Then follows the answer, See the sample for more details.

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
3 1 2
5 2 2
8 3 2</td><td>Case #1: 1
Case #2: 1
Case #3: 2</td></tr></table>


# Constraints



# Note



# Source


