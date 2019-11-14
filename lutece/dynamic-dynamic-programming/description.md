
# Content

There is a common formula of dynamic programming:

![title](/source/lutece/dynamic-dynamic-programming/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTMxMC8yMDE2MDQwMjEwMzU0OTcxMDMuUE5H.PNG)

Now let's make it more dynamic. You will be given the $c_j$ for $1\leq j\leq n$ initially, then there are two types of query:

1. Change $c_j$ to $v$.

2. Return the value of $dp_{i,j}$.

It is guaranteed that $1\leq j\leq n$ for all $j$ above.

# Standard Input

the first line contains two integers $n$ and $m$: the length of the array $c$ and the number of queries.

There are $n$ integers in next line. The $j^{th}$ integer indicates $c_j$.

Then $m$ lines is following, each with a query. There are two types of query:

`1 j v`: Change $c_j$ to $v$.

`2 i j`: Return the value of $dp_{i,j}$.

$1\leq n, m\leq 10^5$

$0\leq c_j, v\leq 10^9$

$0\leq i\leq 20$

$1\leq j \leq n$

# Standard Output

For each query `2 i j`, output the answer in one line. As the answer may be too large, output it modulo $(10^9+7)$ (i.e. if the answer is $X$, you should output $X\ \%\ (10^9+7)$).

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
<tr><td>3 4
1 2 3
2 1 2
2 2 3
1 1 2
2 2 3</td><td>3
10
13</td></tr></table>


# Constraints



# Note



# Source


