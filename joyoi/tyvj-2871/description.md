# 

 
 # 题目描述 
<p>
相传在一个古老的阿拉伯国家里，有一座宫殿。宫殿里有个四四方方的格子迷宫，国王选择驸马的方法非常特殊，也非常简单：公主就站在其中一个方格子上，只要谁能用地毯将除公主站立的地方外的所有地方盖上，美丽漂亮聪慧的公主就是他的人了。公主这一个方格不能用地毯盖住，毯子的形状有所规定，只能有四种选择(如图4-l)：<br><br><center><img src="/source/joyoi/tyvj-2871/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjg3MS9wcm9ibGVtc19pbWFnZXMvMzQxOC9wZy5qcGc=.jpg"></img></center><br>并且每一方格只能用一层地毯，迷宫的大小为(2k)2的方形。当然，也不能让公主无限制的在那儿等，对吧？由于你使用的是计算机，所以实现时间为1s。</p> 

 
 # 输入格式 
<p>
输入文件共2行。<br>第一行：k，即给定被填补迷宫的大小为2k(0<k≤10)；<br>第二行：x y，即给出公主所在方格的坐标(x为行坐标，y为列坐标)，x和y之间有一个空格隔开。<br></p> 

 
 # 输出格式 
<p>
将迷宫填补完整的方案：每一补(行)为x y c (x，y为毯子拐角的行坐标和列坐标，c为使用毯子的形状，具体见上面的图1，毯子形状分别用1、2、3、4表示，x、y、c之间用一个空格隔开)。</p> 
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
<tr><td>【样例】
	blank.in					blank.out
	3					5 5 1
	3 3					2 2 4
						1 1 4
						1 4 3
						4 1 2
						4 4 1
						2 7 3
						1 5 4
						1 8 3
						3 6 3
						4 8 1
						7 2 2
						5 1 4
						6 3 2
						8 1 2
						8 4 1
						7 7 1
						6 6 1
						5 8 3
						8 5 2
						8 8 1
</td><td></td></tr></table>
