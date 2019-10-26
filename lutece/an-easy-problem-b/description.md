
# Content

N个数排成一列，每个数的大小为1或者0。有两种操作，第一种操作是把一段区间内的每个数异或1，第二种操作是询问区间内最长连续1的长度。

# Standard Input

第一行一个整数N（1≤N≤100000），表示N个数。第二行N个数。接下来一行一个整数M（1≤M≤100000）,表示M个操作，接下来M行每行三个整数K,L,R。K=1表示把L到R这段区间的数全部异或上1，K=0表示询问L到R这段区间内最长连续1的长度。

# Standard Output

对于每个询问，输出对应的答案，每个询问占一行。

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
<tr><td>5
0 1 0 0 1
5
0 1 4
1 1 1
0 1 4
1 3 4
0 1 4</td><td>1
2
4</td></tr></table>


# Constraints



# Note



# Source


