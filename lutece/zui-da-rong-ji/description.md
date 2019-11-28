
# Content

在 $x$ 轴的正整数坐标 $1, 2, \cdots , N$ 上分别竖立着一条线段，高度分别为 $h_1, h_2, \cdots , h_N$。这样只要我们任意选择两条线段 $i, j$，再加上 $x$ 轴就能围成一个水槽了(只不过是二维的)。

由于短板效应，这个水槽的容积应该是

$$V = S\times h = \left | j-i \right |\times \min(h_i, h_j)$$

那么选哪两条线段与 $x$ 轴构成的水槽容积最大呢？

# Standard Input

输入一共两行：

第一行是一个正整数 $N$，代表一共有多少条线段，其中 $2 < N < 10^6$；

第二行是 $N$ 个正整数 $h_1, h_2, \cdots , h_N$，分别表示线段 $1, 2, \cdots , N$ 的高度，其中 $0\leq h_i < 10^3$。

# Standard Output

输出最大容积。

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
1 3 6 4 2</td><td>6</td></tr></table>


# Constraints



# Note



# Source


