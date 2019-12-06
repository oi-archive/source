
# Content

众所周知，`学姐姐`是个3D的人物，但是有一天`学姐姐`受到了降维打击变成了`子女女`，于是`学姐姐`很生气，想把$3\times 3$矩阵也变成$2\times 3$维的。  
但是不是什么矩阵都会受到`学姐姐`的降维打击，只有一个矩阵C

$$\begin{bmatrix} c_{11} & c_{12} & c_{13} \\\ c_{21} & c_{22} & c_{23} \\\ c_{31} & c_{32} & c_{33} \end{bmatrix}$$

满足存在另一个矩阵X

$$\begin{bmatrix} a_1 & a_2 & a_3 \\\ b_1 & b_2 & b_3 \end{bmatrix} $$

其中$c_{ij} = a_i+b_j$ 才可以降维打击，现在给你矩阵C，求是否可以降维打击。

# Standard Input

输入包括3行，每行3个数表示c矩阵。
$1\le c_{ij}\le 100$

# Standard Output

输出Yes或者No，表示可行不可行

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
<tr><td>1 0 1
2 1 2
1 0 1</td><td>Yes
</td></tr><tr><td>2 2 2
2 1 2
2 2 2</td><td>No
</td></tr></table>


# Constraints



# Note



# Source


