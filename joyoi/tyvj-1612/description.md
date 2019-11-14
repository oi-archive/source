# 

 
 # 题目背景 
百度NOIP吧成功举办了五子棋比赛之后，吧主又准备开始智力比赛 

 
 # 题目描述 
比赛是这样的，有一束光从一个点射入，你可以调整光射入的方向。比赛中可以放置一些镜子来改变光路，使得光通过某一个点，并要求光走过的距离最短。需要注意的是，你必须保证任何时刻光都是沿着正东、正西、正南、正北方向走。<BR>看到这个题目，吧友们都说太简单了，于是准备加大难度，只允许在N个地方放置镜子（也可以不放置）。你的任务就是要找到这个最短距离，并输出它。<BR> 

 
 # 输入格式 
第一行输入一个整数N，表示一共有N个位置可以放置镜子<BR>接下来有N+2行，第2行为起点的坐标，第N+3行是终点的坐标，第3行到第N+2行为可以放置镜子的坐标，坐标均为整数。<BR> 

 
 # 输出格式 
只有一行，输出光走过的最短路径，并保留3位小数。如果无论怎么样，都无法到达终点，则输出“NO”.” 

 
 # 提示 
<img src="/source/joyoi/tyvj-1612/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTYxMi9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL1AxNjEzLmpwZw==.jpg" border=0 align=middle><BR>【数据范围】<BR>对于10%的数据&nbsp;满足N=0<BR>对于30%的数据&nbsp;满足N&lt;=1<BR>对于60%的数据&nbsp;满足N&lt;=1000<BR>对于100%的数据&nbsp;满足N&lt;=100000&nbsp;所有坐标范围的绝对值&lt;=2*10^9<BR> 
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
<tr><td>【输入样例1】
2
0 0
1 1
0 1
1 -1

【输入样例2】
2
0 0
1 1
0 1
2 2
</td><td>【输出样例1】
4.000

【输出样例2】
NO
</td></tr></table>
