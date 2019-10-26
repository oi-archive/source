
# Content

You should have been familiar with the LCS(Longest Common Subsequence) and LIS(Longest Increasing Subsequence problem. Now, here is a challenge for you to solve the combined problem LCIS.

We call sequence $S$ (with length $M$) is a subsequence of $A$ (with length $N$) if there exist $1 \leq i\_1 < i\_2 < \cdots < i\_M \leq N$ so that $S(1)=A\_{i1}, S(2)=A\_{i2},  \cdots ,S(M)=A\_{iM}$

We call sequence $S$ is a common increasing subsequence of $A$ and $B$ if: 
1. $S$ is a subsequence of both $A$ and $B$; 
2. $S$ is strictly increasing, which means $S\_i<S\_{i+1}$($1\leq i <M$)

# Standard Input

In the first line is one integer $T$($T\leq 10$).

$T$ cases follow.In each case you will be given two number sequence $A$ and $B$.

On the first line are two integers $LA$ and $LB$ representing the length of $A$ and $B$.

One the second line are $LA$ integers. The $i\_{th}$ integer is $A\_i$.

One the third line are $LB$ integers. The $i\_{th}$ integer is $B\_i$.

($1\leq LA,LB\leq 1000$ , $1\leq A\_i,B\_i\leq 2^{31}-1$).

# Standard Output

For each case print one line with an integer $L$ standing for the length of the longest common increasing subsequence of $A$ and $B$.

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
6 5
1 3 2 3 4 5
1 2 3 4 5
5 5
5 4 3 2 1
5 4 3 2 1
3 3
1 1 1
1 1 1</td><td>5
1
1</td></tr></table>


# Constraints



# Note



# Source


