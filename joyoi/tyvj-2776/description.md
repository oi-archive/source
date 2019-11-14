# 

 
 # 题目描述 
<p>
在一个8*8的棋盘上有4个皇后。棋盘的行列范围都是1到8，行从上到下，列从左到右。皇后可以移动，每次移动的规则是：<br>1。把一个皇后移到没有被占据的相邻4个位置中(左，右，上，下)<br>2。如果某个相邻位置被占据了，可以跳过它到另一个空白位置<br>如下图所示：<br><br><center><img src="/source/joyoi/tyvj-2776/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc3Ni9wcm9ibGVtc19pbWFnZXMvMzI5NS9wZy5naWY=.gif"></img></center><br>写一个程序实现：从输入文件中读入两个棋盘状态，证明第二个状态是否可以由第一个状态最多经过8步移动得到，输出结果到输出文件。</p> 

 
 # 输入格式 
<p>
可能有多个测试数据,数据的个数不超过10。每个测试数据两行，每行8个整数，描述棋盘上4个皇后的位置，每个皇后两个整数，表示行和列。</p> 

 
 # 输出格式 
<p>
每个测试数据输出一行，如果能实现输出”YES”,否则输出”NO”。</p> 
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
<tr><td>4 4 4 5 5 4 6 5
2 4 3 3 3 6 4 6
</td><td>YES</td></tr></table>
