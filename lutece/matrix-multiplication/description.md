
# Content

When calculating $A(r \times s)  \times  B(s \times t)$ ($A$ and $B$ are matrix),we do $r \times s \times t$ times of standard multiplication.

When calculating $A\_1 \times A\_2 \times \cdots \times A\_N( A\_i(1 \leq i \leq N)$ is matrix with size $a\_i \times a\_{i+1} )$,if we calculate it from left to right we will have to do a1*a2*a3+a1*a3*a4+...+a1*aN*a(N+1) times of multiplications.But as is known ,matrix multiplication is associative$( (A \times B) \times C=A \times (B \times C) )$. So we can do less multiplications if we select a proper order to calculate it.

What bothers us is the minimum times of multiplications necessary to calculate $A\_1 \times A\_2 \times \cdots \times A\_N$

# Standard Input

In the first line is an integer $T(T \leq 10)$

Followed by $T$ cases.In each case there're $2$ lines:

An integer $N(2 \leq N \leq 100)$ is given in the first line

The next line contains $N+1$ integers $a\_i(1\leq a\_i \leq 100)$ which define the size of matrices as described above.

# Standard Output

For each case output one integer on a single line standing for the minimum times of multiplicaions needed.

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
3
2 3 4 1</td><td>18</td></tr></table>


# Constraints



# Note

In the Sample Input there're $3$ matrices $A\_1$ $A\_2$ $A\_3$ with size $2 \times 3 , 3 \times 4$ and $4 \times 1$.

if we calculate $A\_1 \times A\_2 \times A\_3$from left to right as $(A\_1 \times A\_2) \times A\_3 , 2 \times 3 \times 4+2 \times 4 \times 1=32$ times of multiplication is needed.

if we calculate it in following way: $A\_1 \times (A\_2 \times A\_3)$, only $3 \times 4 \times 1+2 \times 3 \times 1=18$ times of multiplications are needed ,and this is the optimal choice.

# Source


