
# Content

柱神要去打Final啦~\(≧▽≦)/~啦啦啦

柱神来到了异国他乡的普吉岛，柱神决定好好游览一番。

普吉岛的景点编号为$1$到$N$，景点之间由双向的道路连接着，所有的道路的长度都是$1$。

柱神希望访问所有的景点，但是又不想耽搁太长的时间，所以柱神决定每天访问一个景点。

为了好好陶冶情操，柱神并不在路上花费太多的时间，所以柱神不会在连续的两天访问两个最短距离超过$K$的景点。

由于柱神忙着打Final，所以旅行的方案就交个你了。

# Standard Input

第一行为两个整数$N,K$，其中$4<=N<=500$，$3<=K<=N-1$。

接下来$N$行$N$列，第$i$行$j$列的值$a\_{ij}=1$或者$a\_{ij}=0$。

如果$a\_{ij}=1$，表示从景点$i$到景点$j$有一条长为$1$的道路，如果$a\_{ij}=0$，则表示从$i$到$j$没有直接的道路。

图保证联通。

注意哦：数据以字符串的形式给出，只包含0和1，且$a\_{ii}=0$

# Standard Output

输出一个$1$到$N$的排列，第$i$个数表示第$i$天访问的景点编号。输出任意一组解即可。

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
<tr><td>4 3
0100
1010
0101
0010</td><td>1 3 2 4</td></tr></table>


# Constraints



# Note



# Source


