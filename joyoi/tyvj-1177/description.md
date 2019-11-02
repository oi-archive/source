# 

 
 # 题目描述 
给出一个简单多边形(没有缺口)，它的边要么是垂直的，要么是水平的。要求计算多边形的面积。<BR>多边形被放置在一个X-Y的卡笛尔平面上，它所有的边都平行于两条坐标轴之一。然后按逆时针方向给出各顶点的坐标值。所有的坐标值都是整数(因此多边形的面积也为整数)。<BR> 

 
 # 输入格式 
第一行给出多边形的顶点数n(n≤100)。接下来的n行每行给出多边形一个顶点的坐标值X和Y(都为整数并且用空格隔开)。顶点按逆时针方向逐个给出。并且多边形的每一个顶点的坐标值-200≤x,y≤200。多边形最后是靠从最后一个顶点到第一个顶点画一条边来封闭的。 

 
 # 输出格式 
仅有一行,包含一个整数，表示多边形的面积。<BR> 

 
 # 提示 
<img src="/source/joyoi/tyvj-1177/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTE3Ny9Qcm9ibGVtSW1nXDExNzctMS5qcGc=.jpg" border=0 align=middle> 
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
<tr><td>10
0 0
4 0
4 1
3 1
3 3
2 3
2 2
1 2
1 3
0 3
</td><td>9
</td></tr></table>
