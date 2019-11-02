# 

 
 # 题目背景 
APIO2010 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;在一个地区中有&nbsp;n个村庄，编号为1,&nbsp;2,&nbsp;...,&nbsp;n。有n&nbsp;–&nbsp;1条道路连接着这些村庄，每条道路刚好连接两个村庄，从任何一个村庄，都可以通过这些道路到达其他任一个村庄。每条道路的长度均为&nbsp;1个单位。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;为保证该地区的安全，巡警车每天要到所有的道路上巡逻。警察局设在编号为1的村庄里，每天巡警车总是从警察局出发，最终又回到警察局。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;下图表示一个有8个村庄的地区，其中村庄用圆表示（其中村庄&nbsp;1用黑色的<BR>圆表示），道路是连接这些圆的线段。为了遍历所有的道路，巡警车需要走的距<BR>离为14&nbsp;个单位，每条道路都需要经过两次。&nbsp;<BR><img src="/source/joyoi/tyvj-1216/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIxNi9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nLzEyMTYtMS5qcGc=.jpg" border=0 align=middle><BR>&nbsp;&nbsp;&nbsp;&nbsp;为了减少总的巡逻距离，该地区准备在这些村庄之间建立&nbsp;K&nbsp;条新的道路，每条新道路可以连接任意两个村庄。两条新道路可以在同一个村庄会合或结束（见下面的图例（c）&nbsp;）。一条新道路甚至可以是一个环，即，其两端连接到同一个村庄。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;由于资金有限，K&nbsp;只能是&nbsp;1或2。同时，为了不浪费资金，每天巡警车必须经过新建的道路正好一次。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;下图给出了一些建立新道路的例子：&nbsp;<BR><img src="/source/joyoi/tyvj-1216/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIxNi9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nLzEyMTYtMi5qcGc=.jpg" border=0 align=middle><BR>&nbsp;&nbsp;&nbsp;&nbsp;在(a)中，新建了一条道路，总的距离是&nbsp;11。在(b)中，新建了两条道路，总的巡逻距离是&nbsp;10。在(c)中，新建了两条道路，但由于巡警车要经过每条新道路正好一次，总的距离变为了&nbsp;15。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;试编写一个程序，读取村庄间道路的信息和需要新建的道路数，计算出最佳的新建道路的方案使得总的巡逻距离最小，并输出这个最小的巡逻距离。&nbsp; 

 
 # 输入格式 
第一行包含两个整数&nbsp;n,&nbsp;K(1&nbsp;≤&nbsp;K&nbsp;≤&nbsp;2)。接下来&nbsp;n&nbsp;–&nbsp;1行，每行两个整数&nbsp;a,&nbsp;b，<BR>表示村庄a与b之间有一条道路(1&nbsp;≤&nbsp;a,&nbsp;b&nbsp;≤&nbsp;n)。<BR> 

 
 # 输出格式 
输出一个整数，表示新建了K&nbsp;条道路后能达到的最小巡逻距离。<BR> 

 
 # 提示 
【数据范围】&nbsp;<BR>10%的数据中，n&nbsp;≤&nbsp;1000,&nbsp;&nbsp;&nbsp;&nbsp;K&nbsp;=&nbsp;1；&nbsp;<BR>30%的数据中，K&nbsp;=&nbsp;1；&nbsp;<BR>80%的数据中，每个村庄相邻的村庄数不超过&nbsp;25；&nbsp;<BR>90%的数据中，每个村庄相邻的村庄数不超过&nbsp;150；&nbsp;<BR>100%的数据中，3&nbsp;≤&nbsp;n&nbsp;≤&nbsp;100,000,&nbsp;1&nbsp;≤&nbsp;K&nbsp;≤&nbsp;2。&nbsp; 
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
<tr><td>8 1 
1 2 
3 1 
3 4 
5 3 
7 5 
8 5 
5 6 </td><td>11 </td></tr></table>
