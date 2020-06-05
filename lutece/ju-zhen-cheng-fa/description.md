
# Content

在线性代数课中，Cjj 学到了一个重要的知识点——矩阵乘法。

对于两个矩阵 $A$ 和 $B$，它们的乘积 $AB$ 有意义当且仅当 $A$ 的列数等于 $B$ 的行数。如果 $A$ 是一个 $n \times m$ 矩阵，$B$ 是一个 $m \times p$ 矩阵，那么它们的乘积 $AB$ 就是一个 $n \times p$ 矩阵。

我们可以推广到任意数量矩阵的乘法。对于矩阵 $A_1, A_2, \ldots, A_n$，如果对任意的 $i = 1,2, \ldots, n – 1$，$A_i$ 的列数等于 $A_{i+1}$ 的行数，那么它们的乘积 $A_1 A_2 \cdots A_n$ 是有意义的。乘积矩阵的行数就是 $A_1$ 的行数，列数就是 $A_n$ 的列数。

学会了矩阵乘法后，Cjj 晚上做了个梦，他梦见他面前出现了 $n$ 个矩阵 $A_1, A_2, \ldots, A_n$，并且他知道每个矩阵的行数与列数。Cjj 想知道，是否存在一种排列，使得这些矩阵的乘积有意义。具体地说，是否存在一种 $1$ 到 $n$ 的排列 $p_1, p_2, \ldots, p_n$，使得乘积 $A_{p_1} A_{p_2} \ldots A_{p_n}$ 有意义。如果存在，他还想知道乘积矩阵的元素个数（即行数乘以列数）最大是多少。

# Standard Input

第一行包含一个整数 $n$ ($1 \le n \le 10^5$)，表示矩阵的个数。  

接下来的 $n$ 行，第 $i$ 行包含两个整数 $x_i$ 和 $y_i$ ($1 \le x_i,y_i \le 100$)，表示矩阵 $A_i$ 有 $x_i$ 行和 $y_i$ 列。

# Standard Output

如果存在一种排列使得矩阵乘积有意义，输出乘积矩阵元素个数的最大值。如果不存在，输出 $-1$。

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
1 3</td><td>-1</td></tr></table>


# Constraints



# Note

对于第一组样例， $A_1$ 是 $2 \times 3$ 矩阵，$A_2$ 是 $1 \times 2$ 矩阵，$A_3$ 是 $3 \times 4$ 矩阵。乘积 $A_2 A_1 A_3$ 有意义，是 $1 \times 4$ 矩阵，元素个数为 $4$。

# Source


