
# Content

![pic](/source/lutece/linear-algebra/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMTcvZTRDdkRKRzdUTHRIaVBrLnBuZw==.png)

Cjj is learning linear algebra. He thinks matrix multiplication is very interesting.

As we know, given two matrices $A$ and $B$, the product $AB$ is defined if and only if the number of columns in $A$ equals the number of rows in $B$. In more detail, if $A$ is an $n \times m$ matrix and $B$ is an $m \times p$ matrix, the product $AB$ is an $n \times p$ matrix.

This extends naturally to the product of any number of matrices. That is, if $A_1, A_2, \ldots, A_n$ are matrices such that the number of columns in $A_i$ equals the number of rows in $A_{i+1}$ for $i = 1, \ldots, n-1$, then the product is $A_1 A_2 \cdots A_n$. The number of rows in the product equals the number of rows in $A_1$. The number of columns in the product equals the number of columns in $A_n$.

After learning matrix multiplication, Cjj writes down $n$ matrices $A_1, A_2, \ldots, A_n$. They can be multiplied together as $A_1 A_2 \cdots A_n$. But evil Macaron_lin wants to destroy his work, so he rearranges the order of these matrices. Now given the rearranged matrices, can you help Cjj calculate their product? To simplify the problem, we just give you the number of rows and columns in a matrix, and you just need to calculate the number of elements in the product.

# Standard Input

The first line contains an integer $n$ ($2 \le n \le 10^5$) — the number of matrices.

The next $n$ lines describe the matrices. The $i$-th line contains two intergers $x_i$ and $y_i$ ($1 \le x_i,y_i \le 100$), which means the $i$-th matrix has $x_i$ rows and $y_i$ columns. Please note that the order of matrices is rearranged.

It is guaranteed that there is at least one possible solution.

# Standard Output

Print the number of elements in the product. If there are multiple solutions, print the maximum one.

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
2 3
1 2
3 4</td><td>4</td></tr><tr><td>2
1 2
2 1</td><td>4</td></tr></table>


# Constraints

In the fisrt sample, $A_1$ is a $1 \times 2$ matrix, $A_2$ is a $2 \times 3$ matrix, and $A_3$ is a $3 \times 4$ matrix. The product $A_1 A_2 A_3$ is an $1 \times 4$ matrix. There are $1 \times 4 = 4$ elements in the product.

In the second sample, there are two solutions:

1. $A_1$ is a $1 \times 2$ matrix, and $A_2$ is a $2 \times 1$ matrix. The product $A_1 A_2$ is a $1 \times 1$ matrix. There is $1 \times 1=1$ element in the product.
2. $A_1$ is a $2 \times 1$ matrix, and $A_2$ is a $1 \times 2$ matrix. The product $A_1 A_2$ is a $2 \times 2$ matrix. There are $2 \times 2=4$ elements in the product.

The maximum number is $4$.

# Note



# Source


