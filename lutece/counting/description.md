
# Content

In a math class,you are assigned the following task.

First,look at the definition $F(n,d)=k$ which means that in the given number $n$,there are $k$ $d$'s.

For instance, $F(311,1)=2$, $F(311,3)=1$

For the given $(n,k,d)$ you are to find how many $i'$s which can meet the constraits below
1. $1\leq i\leq n$
2. $F(i,d)=k$

# Standard Input

Multiple lines ended with `EOF`

Each line contains three integers $n$($1\leq n<2^{31}$), $k$($1\leq k\leq 9$), $d(1\leq d\leq 9$)

# Standard Output

A single integer

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
<tr><td>14 1 1
123 2 2
876 2 3</td><td>5
2
26</td></tr></table>


# Constraints



# Note

For the first case,there are $5$ numbers $(1,10,12,13,14)$

For the second case,there are $2$ numbers $(22,122)$

# Source


