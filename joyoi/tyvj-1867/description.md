# 

 
 # 题目描述 
夏天，也许大家热爱在水中畅游，体验炎炎夏日中难得的清爽。可是，游泳运动中的事故也是层出不穷的。因此，游泳馆设计了一套救援方案，请你来帮忙进行评估。<BR>游泳池可以看成一个二维平面。当且仅当一个点的横纵坐标都为整数的时候，这个点为整点。平面当中每个整点上都有一名游泳的同学，他们的移动忽略不计。救生员同样处于整点位置上。由于不同的救生员能力不同，他们所能够保护的范围形状、大小也是不一样的。救生员的保护范围有三角形、正方形、圆形三种形状。现在，给出N名救生员的保护范围，如果一个同学在某一个救生员的保护范围内，那么这个同学是被保护的。请你计算能够被保护的同学人数。数据保证每个救生员的保护面积大于0.<BR><img src="/source/joyoi/tyvj-1867/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTg2Ny9odHRwOi8vZmlsZS0wMi5ibG9nY24uY29tL3dwMDIvTTAwLzA1L0Y3L3dLZ0tDMUFyWXZvQUFBQUFBQUJ4RFZLN29FazQ2Ni5qcGc=.jpg" border=0 align=middle> 

 
 # 输入格式 
第一行一个整数N，表示救生员的人数。<BR>接下来N行描述N个救生员的保护范围：<BR>如果这个救生员的保护范围是三角形，那么将输入"T&nbsp;x1&nbsp;y1&nbsp;x2&nbsp;y2&nbsp;x3&nbsp;y3"，其中，(x1,y1）、（x2,y2)、(x3,y3)是三角形的三个顶点坐标。<BR>如果这个救生员的保护范围是圆形，那么将输入"C&nbsp;x&nbsp;y&nbsp;r"，其中，(x,y)是圆心，r是圆的半径。<BR>如果这个救生员的保护范围是正方形，那么将输入"S&nbsp;x&nbsp;y&nbsp;l"，其中，(x,y)是正方形左下角坐标，l是正方形的边长。<BR>特别地，如果一个整点在图形的边界上，在这个点上的同学将被认为是被保护的。 

 
 # 输出格式 
一行一个整数，表示被保护的同学的人数。 

 
 # 提示 
样例解释：如图所示，红色的点表示被保护的同学。<BR>对于100%的数据，所有数字均为正整数且不大于50.<BR>对于70%的数据，救生员保护范围只有圆形和正方形。From&nbsp;-&nbsp;This_poet<BR>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com&nbsp;/&nbsp;Freda.RD.Shi@gmail.com<BR>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>3
C 10 10 3
S 9 8 4
T 7 9 10 8 8 10</td><td>34
</td></tr></table>
