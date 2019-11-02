# 

 
 # 题目描述 
在平面上有&nbsp;n&nbsp;个点（n&nbsp;&lt;=&nbsp;50），每个点用一对整数坐标表示。例如：当&nbsp;n＝4&nbsp;时，4个点的坐标分另为：p1（1，1），p2（2，2），p3（3，6），P4（0，7），见图一。<BR><img src="/source/joyoi/tyvj-1899/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTg5OS8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEwMzMuanBn.jpg" border=0 align=middle>　　这些点可以用&nbsp;k&nbsp;个矩形（1&lt;=k&lt;=4）全部覆盖，矩形的边平行于坐标轴。当&nbsp;k=2&nbsp;时，可用如图二的两个矩形&nbsp;sl，s2&nbsp;覆盖，s1，s2&nbsp;面积和为&nbsp;4。问题是当&nbsp;n&nbsp;个点坐标和&nbsp;k&nbsp;给出后，怎样才能使得覆盖所有点的&nbsp;k&nbsp;个矩形的面积之和为最小呢。约定：覆盖一个点的矩形面积为&nbsp;0；覆盖平行于坐标轴直线上点的矩形面积也为0。各个矩形必须完全分开（边线与顶点也都不能重合）。&nbsp;<BR> 

 
 # 输入格式 
第一行n和k<BR>下面n行为每一个矩形的坐标（0&lt;=xi,yi&lt;=500)&nbsp; 

 
 # 输出格式 
一个整数，即满足条件的最小的矩形面积之和。 

 
 # 提示 
Noip2002提高组第4题 
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
1 1
2 2
3 6
0 7
</td><td>4
</td></tr></table>
