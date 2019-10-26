
# Content

秦队长是一个天才，他经常有一些无敌的想法。
一天，他在坐标纸上写写画画，发现一些点连接起来可以出现很美丽的图案。
于是，作为英明神武的acm集训队队长，他想如果随机给出平面上一些点的坐标，能否用这些点连接成一棵二叉树，并且这棵二叉树的边权和最小。二叉树的边权就是两点之间的欧几里得距离。
对于平面上的二叉树，所有的边都是自上而下的，就是对于一条边是从$u$到$v$，必然满足$u$的纵坐标严格大于$v$的纵坐标

# Standard Input

第一行是一个$n$(2<=$n$<=400)表示平面上点的个数
接下来的n行，每行两个整数$x_i、y_i (|x_i|,|y_i| <= 1e3)$，表示每个点的坐标

# Standard Output

输出最小权值，结果保留6位小数，如果不存在满足要求的二叉树，那么输出$“-1”$。

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
0 0
1 0
2 1</td><td>3.650281539872885</td></tr></table>


# Constraints



# Note



# Source


