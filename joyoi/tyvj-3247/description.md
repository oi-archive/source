# 

 
 # 题目描述 
<p>
多边形面积（area.pas/c/cpp）<br><br>【问题描述】<br><br>中学生杰利陶醉于数学研究，他思考的问题对专家而言可能太过简单，但作为一个15岁的中学生来说，他做得非常棒。他太热衷于思考数学问题，以至于轻易就会尝试用数学方法来解决碰到的问题。一天，他看到桌上的一张纸。他四岁的妹妹玛丽在上面画了一些线。那些线恰好构成一个凹多边形，如图1所示。<br><br><center><img src="/source/joyoi/tyvj-3247/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI0Ny9wcm9ibGVtc19pbWFnZXMvMTgwNS9wMS5naWY=.gif"></img></center><br>“棒极了!”他想，“这些多边形看起来是规则的。我曾经学过怎样计算三解形、矩形和圆的面积。我一定能找到计算这些图形面积的方法。”他确实做到了。首先，他标记多边形顶点的坐标，如图2所示。随后，他豪不费力的求得结果----0.75 。<br><br><center><img src="/source/joyoi/tyvj-3247/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI0Ny9wcm9ibGVtc19pbWFnZXMvMTgwNS9wMi5naWY=.gif"></img></center><br>当然，他不会满足于解决这么简单的问题。“嗯，如果纸上面的是一个任意的多边形，我应该怎么计算它的面积呢？”他问自己。可他一直都没有找到计算任意多边形面积的通用方法。他清楚地明白以他的能力无法找到问题的答案。所以他向你请教。他会很感激你好心的帮助。<br><br></p> 

 
 # 输入格式 
<p>
输入数据的第一行是一个整数n，代表图形的顶点个数(1=<n<=1000)。<br>接下来的N行，每行是一对实数，代表图形的顶点的坐标(xi,yi)。每个图形由第一个顶点连接第二个顶点，第二个顶点连接第三个顶点，…，最后第N个顶点连接第一个顶点形成封闭的多边形。</p> 

 
 # 输出格式 
<p>
输出图形的面积或字符串“Impossible”。<br>如果图形是一个多边形，计算它的面积(精确到小数后两位)。如果输入的顶点不能构成一个多边形(也就是说，一条边和另一条不相连的边相交，例如，四条线段的图形，第一条线和第三条线段相交)，就输出“Impossible”，指出图形不可能是多边形。如果顶点的数量不足以构成一个封闭的多边形，也输出“Impossible”。</p> 
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
<tr><td>样例一
5
0 0
0 1
0.5 0.5
1 1
1 0

样例二
4
0 0
0 1
1 0
1 1</td><td>样例一
0.75

样例二
Impossible</td></tr></table>
