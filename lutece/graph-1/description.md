
# Content

一个$w*h$的网格中，有n个格点组成的简单多边形(不自交)，现在请你按照以下规则绘制该多边形  
按照每个网格中多边形所占面积，给每个网格打上标记，标记符号如下  

>[0%,25%)-----------------"."  
>[25%,50%)----------------"+"  
>[50%,75%)----------------"o"  
>[75%,100%)---------------"$"  
>100%---------------------"#"  

将网格打好标记之后输出，更多细节请参见样例

# Standard Input

第一行为三个整数$N$,$W$,$H$

接下来$N$行每行两个整数$x_i$,$y_i$，表示第i个点的坐标，顺时针给出

# Standard Output

输出$H$行，每一行$W$个字符，每个字符表示每个网格的标记

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
<tr><td>6 8 7
7 6
1 0
1 7
5 5
2 4
2 3</td><td>.$+.....
.##$+...
.#$oo+..
.#+$o...
.##o....
.#o.....
.o......</td></tr></table>


# Constraints



# Note



# Source


