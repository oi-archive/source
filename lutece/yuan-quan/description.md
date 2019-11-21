
# Content

给$n$个点，再给一个点$A$，保证$n+1$个点中没有三点共线。

根据数学常识，我们知道平面上$3$个点可以确定一个圆的位置，那么通过这$n$个点 (不包含点$A$)，显然我们 可以得到$C_n^3$个圆

现在，请问这些圆中有多少个圆包含点$A$。(数据保证点$A$不在任意一个圆上)

# Standard Input

输入一个整数$n$，表示总共有$n$个点

接下来$n$行，每行有两个整数$x_i$和$y_i$，表示点的坐标

最后一行包含两个整数，表示点$A$的坐标

# Standard Output

输出一个整数，表示符合条件的圆的数量

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
0 3
3 0
1 1
-1 -2
0 0</td><td>3</td></tr></table>


# Constraints



# Note

$10\%$的数据，$3≤n≤50$。

$30\%$的数据，$3≤n≤500$。

$100\%$的数据，$3≤n≤2000，|x_i|,|y_i|≤10^5$。

# Source


