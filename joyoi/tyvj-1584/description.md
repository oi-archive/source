# 

 
 # 题目描述 
新一届智能车大赛在JL大学开始啦！比赛赛道可以看作是由n个矩形区域拼接而成（如下图所示），每个矩形的边都平行于坐标轴，第i个矩形区域的左下角和右上角坐标分别为(xi,1,yi,1)和(xi,2,yi,2)。&nbsp;题目保证：xi,1&lt;xi,2=xi+1,1，且yi,1&lt;&nbsp;yi,2，相邻两个矩形一定有重叠在一起的边（如图中虚线所示），智能车可以通过这部分穿梭于矩形区域之间。<BR><img src="/source/joyoi/tyvj-1584/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTU4NC9Qcm9ibGVtSW1nLzE1ODQtMS5qcGc=.jpg" border=0 align=middle><BR>选手们需要在最快的时间内让自己设计的智能车从一个给定的起点S点到达一个给定的终点T点，且智能车不能跑出赛道。假定智能车的速度恒为v且转向不消耗任何时间，你能算出最快需要多少时间完成比赛么？<BR> 

 
 # 输入格式 
输入的第一行包含一个正整数n，表示组成赛道的矩形个数。&nbsp;<BR>接下来n行描述这些矩形，其中第i行包含4个整数xi,1,&nbsp;yi,1,&nbsp;xi,2,&nbsp;yi,2，表示第i个矩形左下角和右上角坐标分别为(xi,1,&nbsp;yi,1)和(xi,2,&nbsp;yi,2)。&nbsp;<BR>接下来一行包含两个整数xS,&nbsp;yS，表示起点坐标。&nbsp;接下来一行包含两个整数xT,&nbsp;yT，表示终点坐标。&nbsp;接下来一行包含一个实数v(1≤v≤10&nbsp;)，表示智能车的速度。<BR> 

 
 # 输出格式 
仅输出一个实数，至少精确到小数点后第六位，为智能车完成比赛的最快时间。<BR>温馨提示：由于本题未添加SpecialJudge，请保留10位小数输出。<BR> 

 
 # 提示 
<img src="/source/joyoi/tyvj-1584/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTU4NC9Qcm9ibGVtSW1nLzE1ODQtMi5qcGc=.jpg" border=0 align=middle><BR> 
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
<tr><td>2
1 1 2 2
2 0 3 4
1 1
3 0
1.0
</td><td>2.4142135624
</td></tr></table>
