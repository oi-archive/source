# 

 
 # 题目背景 
JSOI2009第二轮一试 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;聪聪研究发现，荒岛野人总是过着群居的生活，但是，并不是整个荒岛上的所有野人都属于同一个部落，野人们总是拉帮结派形成属于自己的部落，不同的部落之间则经常发生争斗。只是，这一切都成为谜团了——聪聪根本就不知道部落究竟是如何分布的。<BR>&nbsp;&nbsp;&nbsp;&nbsp;不过好消息是，聪聪得到了一份荒岛的地图。地图上标注了N个野人居住的地点（可以看作是平面上的坐标）。我们知道，同一个部落的野人总是生活在附近。我们把两个部落的距离，定义为部落中距离最近的那两个居住点的距离。聪聪还获得了一个有意义的信息——这些野人总共被分为了K个部落！这真是个好消息。聪聪希望从这些信息里挖掘出所有部落的详细信息。他正在尝试这样一种算法：<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于任意一种部落划分的方法，都能够求出两个部落之间的距离，聪聪希望求出一种部落划分的方法，使靠得最近的两个部落尽可能远离。<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如，下面的左图表示了一个好的划分，而右图则不是。请你编程帮助聪聪解决这个难题。<BR><img src="/source/joyoi/tyvj-1843/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTg0My9Qcm9ibGVtSW1nLzE4NDMuanBn.jpg" border=0 align=middle><BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件第一行包含两个整数N和K(1&lt;=N&lt;=1000,1&lt;K&lt;=N)，分别代表了野人居住点的数量和部落的数量。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来N行，每行包含两个正整数x,y，描述了一个居住点的坐标(0&lt;=x,&nbsp;y&lt;=10000)。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出一行，为最优划分时，最近的两个部落的距离，精确到小数点后两位。 
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
<tr><td>4 2
0 0
0 1
1 1
1 0

9 3
2 2
2 3
3 2
3 3
3 5
3 6
4 6
6 2
6 3</td><td>1.00
2.00</td></tr></table>
