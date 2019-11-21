
# Content

定义矩阵两个元素的距离为两个元素行下标差的绝对值与列下标差的绝对值之和。任给一个$m$行$n$列的实数矩阵(每个元素有两位小数，$1\leq m,n\leq 50$)，计算与矩阵每个元素距离小于等于$1$的元素的平均值并取代该元素，输出结果矩阵。要求每个元素保留两位小数。

# Standard Input

输入的第一行是数据组数$T$，其后是$T$组测试数据。每组数组的第一行是整数$m$和$n$，表示随后有$m$行 $n$列的实数矩阵，$m$和$n$之间用一个空格隔开，矩阵元素的每个元素后有一个空格。两组数据间有一个空行。元素的范围为$[0,500]$。

# Standard Output

对应每组输入数据，输出一个结果矩阵，没一个数字保留两位小数，并且后面有一个空格。
每组输出后有一个空行。

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
3 3
1.00 2.00 3.00 
4.00 5.00 6.00 
7.00 8.00 9.00 

1 3
1.00 2.00 3.00</td><td>2.33 2.75 3.67 
4.25 5.00 5.75 
6.33 7.25 7.67 

1.50 2.00 2.50</td></tr></table>


# Constraints



# Note



# Source


