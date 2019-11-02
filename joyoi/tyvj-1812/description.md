# 

 
 # 题目描述 
小鼠a与小鼠b身处一个m×n的迷宫中，如图所示。每一个方格表示迷宫中的一个房间。这m×n个房间中有一些房间是封闭的，不允许任何人进入。在迷宫中任何位置均可沿上，下，左，右4个方向进入未封闭的房间。小鼠a位于迷宫的(p，q)方格中，它必须找出一条通向小鼠b所在的(r，s)方格的路。请帮助小鼠a找出所有通向小鼠b的最短道路。<BR>对于给定的小鼠的迷宫，编程计算小鼠a通向小鼠b的所有最短道路。<BR><img src="/source/joyoi/tyvj-1812/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgxMi9Qcm9ibGVtSW1nLzE4MTIuYm1w.bmp" border=0 align=middle> 

 
 # 输入格式 
由文件maze.in给出输入数据。第一行有3个正整数n，m，k，分别表示迷宫的行数，列数和封闭的房间数。接下来的k行中，每行2个正整数，表示被封闭的房间所在的行号和列号。最后的2行，每行也有2个正整数，分别表示小鼠a所处的方格(p，q)和小鼠b所处的方格(r，s)。<BR><BR> 

 
 # 输出格式 
将计算出的小鼠a通向小鼠b的最短路长度和有多少条不同的最短路输出到文件maze.out。文件的第一行是最短路长度。文件的第2行是不同的最短路数。<BR>如果小鼠a无法通向小鼠b则输出“No&nbsp;Solution!”。<BR> 

 
 # 提示 
JSOI2008江苏省青少年信息学奥林匹克代表队组队选拔赛第一轮试题 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>8 8 3
3 3
4 5
6 6
2 1
7 7
</td><td>11
96
</td></tr></table>
