
# Content

You are given the following points with integer coordinates on the plane: $M\_0, A\_0, A\_1, \cdots , A\_{n - 1}$, where $n$ is odd number. Now we define the following infinite sequence of points $M\_i$: $M\_i$ is symmetric to $M\_{i - 1}$ according $A\_{(i-1)\rm\ mod\ n}$(for every natural number $i$). Here point $B$ is symmetric to $A$ according $M$, if $M$ is the center of the line segment $AB$. Given index $j$ find the point $M\_j$.

# Standard Input

There are multi-cases. On the first line of each case, you will be given an integer $n$ ($1\leq  n\leq  10^5$), which will be odd, and $j$ ($1\leq  j \leq  10^{18}$), where $j$ is the index of the desired point. The next line contains two space separated integers, the coordinates of $M\_0$. After that $n$ lines follow, where the $i\_{th}$ line contain the space separated integer coordinates of the point $A\_{i - 1}$. The absolute values of all input coordinates will not be greater then $1000$.

# Standard Output

For each case output the coordinates of $M\_j$, space separated.

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
0 0
1 1
2 3
-5 3
3 1
5 5
1000 1000
-1000 1000
3 100</td><td>14 0
1995 1995</td></tr></table>


# Constraints



# Note



# Source


