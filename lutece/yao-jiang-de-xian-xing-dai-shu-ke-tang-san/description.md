
# Content

![](/source/lutece/yao-jiang-de-xian-xing-dai-shu-ke-tang-san/img/aHR0cDovL2ltYWdlcy5jbmJsb2dzLmNvbS9jbmJsb2dzX2NvbS9hdXRza3ktamFkZWsvMTA3NzIxNi9vXyVlNSU4ZCU4MyVlNiU5YiU5YzQuanBn.jpg)

曜不但是学园偶像团体Aqours的一员，还参加着高中生信息学竞赛。    
今天，她刚好学到了图论中用来解决生成树计数问题的Matrix-tree定理，这个定理与行列式脱不开联系。   
于是，她在课后给千歌的辅导中，问她：你能求解一个给定行列式的值吗？    
得益于曜的辅导，千歌用笔来算的话没有什么问题，不过，没学过信息学竞赛的她，用计算机来求解就力不从心了。OI / ACM 大神的你，可以帮帮她吗？

# Standard Input

输入包含多组数据，以EOF结尾。    
每组数据的第一行包含一个正整数n，代表行列式的规模。   
接下来n行，每行n个浮点数，代表该给定的行列式。

# Standard Output

对于每个给定的行列式，输出一行，包含一个浮点数，代表该行列式的值。（保留三位小数）

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
<tr><td>4
6 1 0 0
5 -1 3 -2
0 2 0 0
1 3 4 -3
4
1.0 1.0 -1.0 3.0
-1.0 -1.0 2.0 1.0
2.0 5.0 2.0 4.0
0.5 1.0 1.5 1.0
3
1 2 0
3 1 5
2 4 0</td><td>12.000
16.500
0.000
</td></tr></table>


# Constraints



# Note

n<=100   
不要输出-0.000这样的东西

# Source


