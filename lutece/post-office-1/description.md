
# Content

There are $N(N \leq 1000)$ villages along a straight road, numbered from $1$ to $N$ for simplicity. We know exactly the position of every one (noted pos$[i]$,pos$[i]$ is positive integer and pos$[i] \leq 10^8$). The local authority wants to build a post office for the people living in the range $i$ to j(inclusive). He wants to make the sum of |pos$[k]-$position_of_postoffice| $(i \leq k \leq j)$ is minimum.

# Standard Input

For each test case, the first line is $n$. Then $n$ integer, representing the position of every village and in ascending order. Then a integer $q (q \leq 200000)$, representing the queries. Following $q$ lines, every line consists of two integers $i$ and $j$. the input file is end with `EOF`. Total number of test case is no more than $10$.

Be careful, the position of two villages may be the same.

# Standard Output

For every query of each test case, you tell the minimum sum.

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
1 2 3
2
1 3
2 3</td><td>2
1</td></tr></table>


# Constraints



# Note

Huge input,`scanf` is recommend.

# Source


