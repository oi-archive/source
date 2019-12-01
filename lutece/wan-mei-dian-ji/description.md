
# Content

在$n$维空间内，找到$n+1$个点，使得它们两两间的欧几里得距离均为1

点$x=(x_1,...,x_n)$和点$y=(y_1,...,y_n)$之间的欧几里得距离为

$$d(x,y)=\sqrt{\sum_{i=1}^n{(x_i-y_i)^2}}$$

# Standard Input

输入一个整数$n$，$2\leq n \leq 100$

# Standard Output

输出$n+1$行，每行有$n$个实数，第$i$行第$j$列的数字表示第$i$个点的第$j$个分量。

可以输出任意解，答案正确当且仅当任意两点间的距离和1的差值的绝对值小于$10^{-6}$。

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
<tr><td>2</td><td>0 0
0 1
0.8660254038 0.5</td></tr></table>


# Constraints



# Note

输出请保留尽量多位小数。

当$n=2$时，答案构成了边长为1的等边三角形。

当$n=3$时，答案构成了边长为1的正四面体。

# Source


