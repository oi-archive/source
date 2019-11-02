# 

 
 # 题目描述 
<p>
交通问题(traffic.pas/c/cpp)<br><br>【问题描述】<br>     在2500年，有一个这样的城市:  它的街道都是东西或南北走向的，他们编号都是从1开始的连续的自然数。而每一个街道相交处都有一个交通岗，并配有红绿灯。这个城市里边的人在任何时候都非常遵守交通规则，只有在绿灯的时候才通过交通岗(包括转弯)，绝对不会闯红灯。而且他们只会在交通岗改变他们的行车方向。城市里的每条公路的两端都与别的城市相连。<br>有一天，恐布分子突然控制了这个城市，破坏了这个城市的交通，使得每个交通岗的灯都变成了绿灯。但是如果一旦有车通过了这个交通岗，这个岗则马上变成红灯，别的车无法再在这个交通岗通过。也就是，每个岗只允许一个车次通过。<br>这一天恰好在城市中有N辆车，你的任务就是分析这些车能不能逃离到别的城市。下面是例子的图例，的有的六辆车按图示路线都安全逃离。<br><br><center><img src="/source/joyoi/tyvj-3197/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE5Ny9wcm9ibGVtc19pbWFnZXMvMTYwMi9wMS5naWY=.gif"></img></center></p> 

 
 # 输入格式 
<p>
数据存放在当前目录下的文本文件“traffic.in”中。<br>输入文件由多组数据组成。<br>每一组的第一行由三个整数组成：n、m、k，分别表示这个城市水平，竖直街道的条数，以及在城市里的车的数量。<br>接下来的K行，表示每个汽车的坐标(x,y)，表示x行y列有个小车。每个小车开始都在一个交通岗停靠，一旦开出这个交通岗，这个交通岗的交通灯也要变成红色。<br>当n、m、k为0 0 0时，结束输入。这组不用输出。<br>数据之间用空格分隔。<br></p> 

 
 # 输出格式 
<p>
答案输出到当前目录下的文本文件“traffic.out”中。<br>输出文件里的每组数据输出两行，第一行为“Scenario i”，其中I 表示组数。<br>如果这些车都可以逃离，则在第二行输出：“Solution exists”；否则输出：“No solution available”<br></p> 
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
<tr><td>4 3 6
1 3
1 2
2 1
2 2
3 1
4 2
3 3 9
1 1
1 2
1 3
2 1
2 2
2 3
3 1
3 2
3 3
0 0 0
</td><td>Scenario 1
Solution exists
Scenario 2
No solution available</td></tr></table>
