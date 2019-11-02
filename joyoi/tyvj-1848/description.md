# 

 
 # 题目描述 
一个著名的仓库管理公司＊ERKOI请你的公司为其安装一套闭路监视系统。由于&nbsp;SERKOI财力有限，每个房间只能安装一台摄像机作监视用，不过它的镜头可以向任意方向旋转。<BR>首要的问题是确定摄像机的位置以确保房间的每一个角落都能被它监视到。例如，图一和图二是某两个房间的示意图，每个房间用一个封闭的多边形表示，图中的每条边表示一面墙。对于图一所示的房间，我们将摄像机安置在标黑点的位置就能满足要求；而对于图二所示的房间，无论将摄像机安置在那里都无法使其满足要求。<BR><img src="/source/joyoi/tyvj-1848/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTg0OC9Qcm9ibGVtSW1nLzE4NDguanBn.jpg" border=0 align=middle><BR>写一个程序，对于给定的房间示意图，判断是否有可能在这个房间中的某一位置安置一台摄像机，使其能监视到这个房间的任何一个角落。 

 
 # 输入格式 
输入文件包含一个或多个房间示意图的描述信息。每个描述信息的第一行是一一个正整数n（4＜=n＜=100），表示该房间的示意图为一个n边形。以下n行每行包括用空格符隔开的两个整数x,y,按顺时针方向依次为这个n边形的n个顶点在直角坐标系中的的横纵坐标，x,y,的范围在：-1000至1000之间。若n等于0则表示输入文件结束。 

 
 # 输出格式 
对于每个房间，首先输出一行该房间的编号信息“Room&nbsp;＃k：”，k按照输入次序从1开始计数。紧接着一行是判断结果，如果摄像机在房间中某处安置能满足条件，输出：&nbsp;“surveillance&nbsp;is&nbsp;possible。”，否则输出“surveillance&nbsp;is&nbsp;impossible。”&nbsp;每两个房间的输出结果之间用一个空行隔开。 
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
<tr><td>4
0 0
0 1
1 1
1 0
8
0 0 
3 0
4 3
2 2
3 4
4 4
4 5
0 5
0
</td><td>Room #1:
Surveillance is possible.

Room #2:
Surveillance is impossible.
</td></tr></table>
