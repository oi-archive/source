
# Content

Given an Array $A$ with length $N$ ($1 \leq N \leq 5 \cdot 10^5$), find a longest consecutive sub-interval on Array $A$ satisfied that there is no more than 1 minimum number and no more than 1 maximum number in the sub-interval.

# Standard Input

The first line contains an integer $N$ ($1 \leq N \leq 5 \cdot 10^5$) meaning the length of Array $A$.

The second line contains $N$ integers $A_1, A_2 , .... ,A_n$ ($-10^9 \leq A_i \leq 10^9$).

# Standard Output

Output two integers $L$ and $From$ representing the length of the longest consecutive sub-interval on Array $A$ satisfied the condition and the starting position in Array $A$ (starts from 1).

If there are multiple answers, you can output any of them.

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
10</td><td>1 1</td></tr><tr><td>10
8 3 2 5 2 3 4 6 3 6</td><td>6 4</td></tr><tr><td>10
-1 2 -1 2 1 1 2 -1 0 0</td><td>6 5</td></tr></table>


# Constraints



# Note



# Source


