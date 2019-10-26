
# Content

这是一个网格迷宫问题，地图的左上角为$（0，0）$，坐标$（i,j）$表示$i$行$j$列。有一个人，他在一个迷宫里，他要去一个目标位置。他站在网格的交叉点上，障碍物在网格内部。他可以用不同的速度前进，每秒可以走$1$格到$3$格。也可以花费一秒的时间向左或向右转。同时他不能撞到障碍物，也不能半个身体在地图外面。现在，他最短要多少秒才能走到目标位置。人的体积是一个半径为$0.5$格的圆。

# Standard Input

题目有多组测试数据。每组包含以下内容:

第一行包含两个整数$n,m(0 \leq n,m \leq 50)$。表示地图的行数和列数。$n,m$为`0 0`时表示结束。

接下来$n$行，每行包含$m$个$0$或$1$的整数。$1$表示障碍物，$0$表示没有障碍物。

接下来一行包含$5$个整数，$x_1,y_1,x_2,y_2,w$。分别表示初始位置和目标位置，以及初始方向。$0、1、2、3$分别表示上右下左。

题目保证输入合法。

# Standard Output

输出仅包含一个整数，如果无解输出`-1`，否则输出最短的时间（单位：秒）。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>9 10
0 0 0 0 0 0 1 0 0 0
0 0 0 0 0 0 0 0 1 0
0 0 0 1 0 0 0 0 0 0
0 0 1 0 0 0 0 0 0 0
0 0 0 0 0 0 1 0 0 0
0 0 0 0 0 1 0 0 0 0
0 0 0 1 1 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0
1 0 0 0 0 0 0 0 1 0
7 2 2 7 2
9 10
0 0 0 0 0 0 1 0 0 0
0 0 0 0 0 0 0 0 1 0
0 0 0 1 0 0 0 0 0 0
0 0 1 0 0 0 0 0 0 0
0 0 0 0 0 0 1 0 0 0
0 0 0 0 0 1 0 0 0 0
0 0 0 1 1 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0
1 0 0 0 0 0 0 0 1 0
7 2 2 7 2
0 0</td><td>12
12</td></tr></table>


# Constraints



# Note

样例如图所示：（蓝色点为出发点，红色点为目标点，红线为路径）

![title](/source/lutece/yi-ge-jian-dan-de-zou-mi-gong-wen-ti/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODUzLzIwMTQwNTAyMTc0MjIyODE1MTAuanBn.jpg)

# Source


