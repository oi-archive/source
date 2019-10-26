
# Content

酱神去杭州赏花。

花展在一条街道上举行，这条街道上有一共有n个节点，自左而右从$1$到$n$编号，$1$号和$n$号是左右两个端点，两个相邻端点之间的距离为$1$.本次花展一共要展出$m$朵花，在第$ti$时刻，有一朵颜值为$bi$的花将在第$ai$个节点展出，如果酱神在$ti$时刻处于第$x$个节点，那么他能获得的开心值为$bi-|x-ai|$，注意这个值可能为负。

在$t=1$的时刻，酱神可以随意从$1$到$n$选出一个节点作为赏花的起点。在接下来的每个单位时间段中，酱神最多能移动$d$的距离。酱神每秒只能移动整数个距离，且任何时刻不能超出街道的范围。

他能获得的最大开心值为多少？

# Standard Input

第一行$3$个数$n,m,d$。

接下来$m$行,每行$3$个数$ai,bi,ti$。

$1\leq n\leq {10}^{5}$,$1\leq m\leq 100$

$1\leq {a}_{i}\leq n$

 $1\leq {b}_{i}\leq {10}^{9}$

 $1\leq {t}_{i}\leq {10}^{9}$

 $1\leq d\leq {10}^{9}$

# Standard Output

输出一个数，酱神的最大开心值。

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
<tr><td>30 4 2
27 3 1
11 4 1
11 4 1
1 2 20
</td><td>-3
</td></tr></table>


# Constraints



# Note



# Source


