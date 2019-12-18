
# Content

As we know, Bi Luo is a magic boy, he always has some excited questions , now a new question comes.

You are given two sequences $A$ and $B$ ,  he wants to caculate the $Excited$ $Value$ of two sequences.

*  $Excited$ $Value$ = $\sum_{i=1}^{N}\sum_{j=1}^M | A_i \oplus (-B_j) + 2\ast ( A_i \& (-B_j) ) | \ast|i-j|$

# Standard Input

First Line is an positive integer $T$ , ( $1 \leq T \leq 10^4$ ) , represents there are $T$ test cases.

For each test case: 

The first line contains two positive integers $N , M$.( $1 \leq N,M \leq 10^5$ )

The second line contains $N$ non-negative integers represents $A_i$.( $1 \leq A_i \leq 10^9$ )

The third line contains $M$ non-negative integers represents $B_i$.( $1 \leq B_i \leq 10^9$ )

You can assume $\sum N + \sum M \leq 2*10^6$

# Standard Output

For tht $i$-$th$ test case , first output Case #i:  , then output one integer represents the Excited Value,because the Excited Value may be large , so you need to output the Excited Value mod $2^{40}$

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
3 3
1 2 3
4 5 6</td><td>Case #1: 24</td></tr></table>


# Constraints



# Note

The symbol of $\bigoplus$ is $XOR$( https://en.wikipedia.org/wiki/Exclusive_or )

The symbol of $\&$ is $AND$ ( https://en.wikipedia.org/wiki/Logical_conjunction )

# Source


