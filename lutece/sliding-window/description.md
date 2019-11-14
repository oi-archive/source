
# Content

An array of size $n\leq 10^6$ is given to you. There is a sliding window of size $k$ which is moving from the very left of the array to the very right. You can only see the $k$ numbers in the window. Each time the sliding window moves rightwards by one position. Following is an example: 

The array is $[1, 3, -1, -3, 5, 3, 6, 7]$, and $k$ is $3$. Window position Minimum value Maximum value 

| Window position | Minimum value | Maximum value | 
|------------------------|:-----------------------:|:---------------------:|
| $[1, 3, -1], -3, 5, 3, 6, 7$ | $-1$ | $3$ 
| $1, [3, -1, -3], 5, 3, 6, 7$ | $-3$ | $3$ 
| $1, 3, [-1, -3, 5], 3, 6, 7$ | $-3$ | $5$
| $1, 3, -1, [-3, 5, 3], 6, 7$ | $-3$ | $5$ 
| $1, 3, -1, -3, [5, 3, 6], 7$ | $3$ | $6$ 
| $1, 3, -1, -3, 5, [3, 6, 7]$ | $3$ | $7$ 

Your task is to determine the maximum and minimum values in the sliding window at each position.

# Standard Input

The input consists of two lines. The first line contains two integers $n$ and $k$ which are the lengths of the array and the sliding window. There are $n$ integers in the second line.

# Standard Output

There are two lines in the output. The first line gives the minimum values in the window at each position, from left to right, respectively. The second line gives the maximum values.

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
<tr><td>8 3
1 3 -1 -3 5 3 6 7</td><td>-1 -3 -3 -3 3 3
3 3 5 5 6 7</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by love8909. So any mistake here does not imply mistake in the offcial judge data.

# Source


