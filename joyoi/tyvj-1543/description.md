# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在一个长宽均为10，入口出口分别为（0，5）、（10，5）的房间里，有几堵墙，每堵墙上有两个缺口，求入口到出口的最短路经。<BR>&nbsp;&nbsp;&nbsp;&nbsp;<img src="/source/joyoi/tyvj-1543/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTU0My9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvMTU0My5qcGc=.jpg" border=0 align=middle><BR> 

 
 # 输入格式 
&nbsp;&nbsp;第一排为n(n&lt;=20)，墙的数目。<BR>&nbsp;&nbsp;接下来n排，每排5个实数x，a1，b1，a2，b2。<BR>&nbsp;&nbsp;x表示墙的横坐标（所有墙都是竖直的），a1-b1和a2-b2之间为空缺。<BR>&nbsp;&nbsp;a1、b1、a2、b2保持递增，x1-xn也是递增的。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;输出最短距离，保留2位小数。&nbsp;<BR> 

 
 # 提示 
&nbsp;&nbsp;Tsuzuki&nbsp;Matsumoto&nbsp;<BR>&nbsp;&nbsp;From&nbsp;ZJU<BR> 
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
4 2 7 8 9
7 3 4.5 6 7
</td><td>10.06
</td></tr></table>
