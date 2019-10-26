
# Content

God Kufeng is the God of Math. However, Kufeng is not so skilled with linear algebra, especially when dealing with matrixes.

One day, Captain Chen has a problem with matrix, here is the problem:

Given a $n\times n$ matrix $A$, what is the solution of $n\times n$ matrix $X$ for the equation $AX + XA = 2A$?

Captain Chen is a nice Captain, he wants to solve the equation only when A is a diagonal matrix, which means $A_{ij} = 0$ holds for all $i \neq j$ .

“That’s easy!” says Kufeng, “the answer is simply $X = I$, when $I$ is the Identity Matrix.”

“But… is it the only solution for the equation above?” Captain Chen asks.

Kufeng cannot answer this question, can you help him?

# Standard Input

The first line of input is a number $n$, giving the size of matrix $A$ and $X$. $(1\leq n\leq 1000)$

Then comes a single line with $n$ numbers, $x\_1, x\_2, \cdots, x\_n$, where $x\_i$ is the value of $A\_{ii}$. $(-10000\leq x\_i\leq 10000)$

# Standard Output

If the answer is unique, output `UNIQUE`, otherwise output `NOT UNIQUE`

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
1 2 3</td><td>UNIQUE</td></tr><tr><td>2
1 -1</td><td>NOT UNIQUE</td></tr></table>


# Constraints



# Note

For the second sample input, $A=\begin{pmatrix}1 & 0 \\\ 0 & -1\end{pmatrix}$, there can be more than one possible solutions for $X$, for example, $X=\begin{pmatrix}1 & 0 \\\ 0 & 1 \end{pmatrix}$ and $X=\begin{pmatrix}1 & 0 \\\ 1 & 1 \end{pmatrix}$ both satisfy the equation, so the answer is not unique.

# Source


