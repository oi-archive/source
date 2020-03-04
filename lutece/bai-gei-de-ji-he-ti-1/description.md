
# Content

给出 $n$ 个矩形的左下角和右上角的坐标，求矩形面积的并。

矩形面积并指的是被矩形覆盖到的面积和，重叠部分仅算一次。

# Standard Input

多组输入，每组首先一个整数 $n$，代表矩形的数量；

接下来 $n$ 行，每行四个整数 $x_1,y_1,x_2,y_2$，代表每个矩形的左下角坐标为 $(x_1,y_1)$，右上角坐标为 $(x_2,y_2)$。

$n=0$ 时读入结束。

# Standard Output

每组一行一个数字，表示矩形面积的并。

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
0 0 10 10
2
0 0 10 10
5 5 6 6
0</td><td>100
100</td></tr></table>


# Constraints



# Note

保证单测试点数据组数不超过 $300$ 组。对于每组数据，$1\le n\le 10^5,1\le x_1<x_2\le 10^5,1\le y_1<y_2\le 10^5$

# Source


