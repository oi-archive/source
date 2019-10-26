
# Content

MM在绘图程序中随意选取了$n$个点（坐标分别为$(x\_i,y\_i)$）。他突然想利用这$n$个点作一个圆。圆的圆心取为$(\frac{\sum x\_i}{n}, \frac{\sum y\_i}{n})$，半径取为$n$个点到该圆心距离的平均值。记在圆外的点有$S\_1$个，在圆内的点有$S\_2$个，请你编程帮MM统计，并输出相应的$S\_1$和$S\_2$。

# Standard Input

含多组测试数据，输入首先是一个整数$T$表示测试数据组数($0<T \leq 150$)。随后有$T$组测试数据，每组数据占一行，第一个数是整数$n$，表明随后有$2n$个整数，每两个数依次表示一个点的$x$坐标和$y$坐标。其中，$5\leq n\leq 100$，坐标范围为$[-1000,1000]$。注意程序输入的数据均为整数。

# Standard Output

对应每组测试数据，输出对应的结果$S\_1$和$S\_2$，两数间用一个空格隔开。

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
9 290 -333 -19 998 561 -580 -113 -868 1000 -645 -266 -817 688 177 -832 -960 342 930 
6 197 553 122 -725 41 -981 -471 -794 -187 -65 40 -475</td><td>4 5
3 3</td></tr></table>


# Constraints



# Note

圆上的点不用计数。

# Source


