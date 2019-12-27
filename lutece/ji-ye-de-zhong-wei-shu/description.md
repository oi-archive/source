
# Content

给你$N$个数，$X_1, X_2, ... , X_N$, 基爷让我们计算任意两个数差的绝对值 $∣X_i - X_j∣$ $(1 ≤ i < j ≤ N )$ 。 这样，我们可以得到 $C_N^2$ 个数。

现在，基爷希望聪明的你能用一个简单的程序求出这 $C_N^2$ 个数的中位数！

# Standard Input

输入有多组数据。

每组数据，第一行一个整数 $N$，第二行给出 $N$ 个整数 $X_1,  X_2,  ... ,  X_N$  （ $|X_i| ≤ 1,000,000,000$;  $3 ≤ N ≤ 100,000$ ）

# Standard Output

按要求输出中位数，每个数占一行。

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
<tr><td>4
1 3 2 4
3
1 10 2</td><td>1
8</td></tr></table>


# Constraints



# Note

当这 $C_N^2$ 个数的个数为偶数 $M$ 的时候，取第 $\lfloor\frac{M}{2}\rfloor$ 个最小的数作为中位数 （ 别问为什么，这就是`基爷的中位数`！ ）

# Source


