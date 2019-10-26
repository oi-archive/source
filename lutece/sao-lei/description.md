
# Content

扫雷是一种常见的游戏。现在我们想改变一下扫雷的规则。

在$n\times n$的方格地图上，地雷可以影响所有曼哈顿距离不大于$k$的位置，现在给出地图中雷的分布，用`*`代表地雷，用`.`代表无雷，请在所有无雷的位置填上对应的数字，表示能够影响到该位置的雷的数量。

在平面上，坐标$(x\_1, y\_1)$的点$P\_1$与坐标$(x\_2, y\_2)$的点$P\_2$的曼哈顿距离为：

$\left | x\_1-x\_2 \right |+\left | y\_1-y\_2 \right |$

# Standard Input

第一行是一个整数$T$($T\leq 10$)表示数据组数。

每组数据第一行包含两个数字$n$和$k$，$n$不大于$20$，$k$不大于$20$;

接下来包含$n$行，每行$n$个字符

`*`代表地雷，`.`代表无雷，字符中间不含空格。

# Standard Output

对于每组数据，输出相应的分布图，有雷的位置输出$-1$,无雷的位置输出对应的数字,每行的相邻两个数用一个空格隔开（每行的最后请不要输出多余的空格）。

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
<tr><td>2
2 1
*.
..
3 2
*..
...
*..</td><td>-1 1
1 0
-1 1 1
2 2 0
-1 1 1</td></tr></table>


# Constraints



# Note



# Source


