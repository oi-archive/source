
# Content

平面直角坐标系内，有$X$个红球、$Y$个黄球和$Z$个蓝球，每个红球的价值为$a$，每个黄球的价值为$b$，每个蓝球的价值为$c$，请你找出一条直线，使这条直线上小球的总价值最大。

# Standard Input

* 第一行三个整数$a,b,c.$
* 接下来一行，一个整数$X.$
* 接下来$X$行，每行两个整数$x\_{b},y\_{b}$代表红球的横、纵坐标。
* 接下来一行，一个整数$Y.$
* 接下来$Y$行，每行两个整数 $x\_{b},y\_{b}$代表黄球的横、纵坐标。
* 接下来一行，一个整数$Z.$
* 接下来$Z$行，每行两个整数 $x\_{b},y\_{b}$代表蓝球的横、纵坐标。
* 小球的大小忽略不计，保证没有两个小球在同一位置。
* 数据范围：    
* $0 \leq X,Y,Z \leq 100$
* $1 \leq a,b,c \leq 10^6$
* $-10^9 \leq x\_{b},y\_{b} \leq 10^9$

# Standard Output

输出仅一行，求得的最大小球总价值。

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
<tr><td>1 1 2
1
0 0
1
1 1
2
2 2
3 3</td><td>6</td></tr><tr><td>3 15 1
4
1 1
1 2
2 4
3 6
3
0 0
2 2
4 8
3
3 3
4 4
5 5</td><td>39</td></tr></table>


# Constraints



# Note

* 样例$1$，选取直线$y=x$，该直线上有$1$个红球、$1$个黄球和$2$个蓝球，总价值$=1×1+1×1+2×2=6$达到最大。
* 样例$2$，选取直线$y=2x$，该直线上有$3$个红球和$2$个黄球，总价值$=3×3+15×2=39$达到最大。

# Source


