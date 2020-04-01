# 

 
 # 题目描述 
又到暑假了，住在城市A的Car想和朋友一起去城市B旅游。她知道每个城市都有四个飞机场，分别位于一个矩形的四个顶点上，同一个城市中两个机场之间有一条笔直的高速铁路，第I个城市中高速铁路了的单位里程价格为Ti，任意两个不同城市的机场之间均有航线，所有航线单位里程的价格均为t。&nbsp;<BR><img src="/source/joyoi/tyvj-1892/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTg5Mi8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvMTAyNS5qcGc=.jpg" border=0 align=middle><BR>　　&nbsp;<BR>注意：图中并没有<BR>标出所有的铁路与航线。<BR>&nbsp;<BR><BR><BR>那么Car应如何安排到城市B的路线才能尽可能的节省花费呢?她发现这并不是一个简单的问题，于是她来向你请教。<BR>任务<BR>找出一条从城市A到B的旅游路线，出发和到达城市中的机场可以任意选取，要求总的花费最少。<BR><BR><BR> 

 
 # 输入格式 
第一行为一个正整数n(0&lt;=n&lt;=10)，表示有n组测试数据。<BR>每组的第一行有四个正整数s，t，A，B。<BR>S(0&lt;S&lt;=100)表示城市的个数，t表示飞机单位里程的价格，A，B分别为城市A，B的序号，(1&lt;=A，B&lt;=S)。<BR>接下来有S行，其中第I行均有7个正整数xi1，yi1，xi2，yi2，xi3，yi3，Ti，这当中的(xi1，yi1)，(xi2，yi2)，(xi3，yi3)分别是第I个城市中任意三个机场的坐标，T&nbsp;I为第I个城市高速铁路单位里程的价格。 

 
 # 输出格式 
共有n行，每行一个数据对应测试数据<BR>要求保留一位小数 
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
<tr><td>1
3 10 1 3
1 1 1 3 3 1 30
2 5 7 4 5 2 1
8 6 8 8 11 6 3</td><td>47.5</td></tr></table>
