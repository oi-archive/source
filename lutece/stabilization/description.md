
# Content

The instability of a array A with length N is defined as $\sum_{i=1}^{N-1}(|A[i+1]-A[i]|)$. In order to stabilize a array, changing every element A[i] to (A[i] xor X) is allowed. What is the smallest non-negative integer X to minimize the instability of a given array?

# Standard Input

There are multiple test cases. The first line of input contains an integer T, indicating the number of test cases. 

For each test case, the first line contains an integer N. Next line contains N integers, indicating the elements of the array. 

T<=10, 0<=A[i]<2^20, 1<=n<=10^5.

# Standard Output

For each test case, output two integers in one line, the smallest non-negative integer X and the minimum of the instability.

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
3
0 3 0
3
1 3 1
</td><td>1 2
0 4
</td></tr></table>


# Constraints



# Note



# Source


