
# Content

The following equation will be constantly valid no matter what values the variable $n$ and $x\_i$ have.
$\sum_{1\leq i, j\leq n, i\neq j} x_ix_j = (\sum_{i=1}^{n}x_i)^2-\sum_{i=1}^{n}x_i^2$
which means, we could yield the sum of cross items product from sum and sum of square. Now the challenge is to calculate the sum cross items product with given sum, sum of squares, sum of cubes and sum of fourth powers.

Here we have to define of sum of $m_{th}$ power items as $\sum_{i=1}^nx_i^m$

In addition, sum of cross items product is defined as:
$\sum_{\forall 1\leq m<l\leq k\Rightarrow 1\leq i_m,i_l\leq n \& i_m\neq i_l}x_{i_1}x_{i_2}\cdots x_{i_k}$

# Standard Input

The first line of the input contains one integer $T$, which indicate the number of test cases. Each test case contains four integers indicating sum, sum of squares, sum of cubes and sum of fourth power in order, and each is in the range of $[-50000,50000]$.

# Standard Output

One line for each test case contains three integers indicating the answer, which are sum of the cross items with $k$ in the range $2\leq k\leq  4$ separated with a blank.

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
10 30 100 354</td><td>35 50 24</td></tr></table>


# Constraints



# Note



# Source


