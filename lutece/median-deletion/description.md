
# Content

The median of a sequence is defined to be the smallest number which is not smaller than half of the numbers in this sequence, and denoted as median{sequence}. For example, median$(1,3,4,7,8)$ is $4$ and median $(1,3,3,4,7,8)$ equals $3$. 

The definition is also fit for integer matrices. However, we need to modify it a little. For numbers with the same value, we define the one with the minimum row number to be smaller. If their row numbers are the same, the one with the minimum column number is smaller.

In this problem, you are given an integer matrix of size $N \times M$. And you are required to do operations to this matrix showed as below:
* Step $1$:	Find the median in this matrix.
* Step $2$:	Delete the row and the column containing the median. This operation will reduce the size of the matrix.
* Step $3$:	End this game if the matrix’s size is $0 \times 0$. Go back to step $1$, otherwise.

We want you to tell us all medians selected.

# Standard Input

The first line of the input is $T$ (no more than $10$), which stands for the number of test cases you need to solve.

There are three integers $N$, $M$ and $X$ listed in a single line, indicating the number of rows, columns of the matrix and a seed needed to generate the matrix. The matrix is denoted by $A$.
 
Represent $A$ with a sequence $B$ in which $B(i \times M + j) = A(i , j)$. Note that, with sequence $B$, we can rebuild matrix $A$. Generate sequence $B$ with following formulates:
1. $B(0) = X$;
2. $B(k = i \times M + j) = (1234 \times (B(k-1) \times i)^2 + 5678 \times B(k-1) \times j + 91011)\ modulo\ 1000000+1$,

$0 < k < N \times M$, $0 \leq i < N$, $0 \leq j < M$;

$1 \leq N \leq 1000$;

$1 \leq M \leq 1000$;

$1 \leq X \leq 1000000$.

# Standard Output

For every test case, you should output `Case #k:` first in a line, where $k$ indicates the case number and counts from $1$.

Print the medians in the order they are selected with each one in a line.

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
2 2 123
1000 10 123456</td><td>Case #1:
789406
810636
Case #2:
498220
498748
497476
496332
493892
488636
485156
487572
477308
476180</td></tr></table>


# Constraints



# Note

In the first test case, the matrix is$\begin{bmatrix}
123 & 789406\\\\ 
810636 & 910284
\end{bmatrix}$

# Source


