
# Content

Runaway是一款有趣的小游戏。  
![title](/source/lutece/tao-tuo-you-xi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTcwMS8yMDE3MDYwNjE5MjYyMDg4MDI0LmpwZw==.jpg)  
在该游戏中，玩家必须给机器人设计一条安全的逃跑路线。游戏开始时，将给出一张N*M的地图，描述了机器人所在的地形。一开始时机器人在左上角（坐标为(0,0)）的位置。地图中存在着一些障碍物，用’X’表示。空地用’.’表示。你只能对机器人下达两种指令：  
1)‘D’：令机器人向下走一步。即机器人的坐标从(r,c)走到(r+1,c)  
2)‘R’：令机器人向右走一步，即机器人的坐标从(r,c)走到(r,c+1)  
当机器人的坐标为(N,i),(0<=i<=M)或者(i,M),(0<=i<=N)时，机器人达到安全区域。玩家通过该关卡。  
每一关卡中，玩家给出的命令个数必须在[MN,MX]范围内。游戏开始后，机器人将不停地按照玩家给出的命令按顺序移动，直到机器人不能移动【机器人不能进入有障碍物的格子中】或者到达安全格子【坐标为(N,i),(0<=i<=M)或者(i,M),(0<=i<=N)】。  
例如玩家给出命令为：DR.机器人将按照DRDRDRDRDRDRDR….一直移动下去。  
 ![title](/source/lutece/tao-tuo-you-xi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTcwMS8yMDE3MDYwNjE5MjcxMzQ2MTI1LmpwZw==.jpg)  
★编程任务  
   现在，告诉你初始的关卡信息，请设计一个程序，输出可行方案。所以，输出的方案必须使得命令个数尽量少，如果依旧存在多种解则请输出字典序最小的一种。无解输出“-1”。

# Standard Input

每组输入数据中大约有300组测试数据，每组数据以EOF结束，每组测试数据格式如下：  
第一行包含4个整数N,M,MN,MX分别用空格隔开.其中1<N<=100; 1<M<=100; 1<MN<MX<=N+M  
接下来N行，每行M个字符表示N*M的地图信息，其中’X’表示障碍物，’.’表示空白地。数据保证(0，0)点为’.’。

# Standard Output

对于每组数据，请输出一行，为一种合法的方案。输出的方案必须使得命令个数尽量少，如果依旧存在多种解则请输出字典序最小的一种，无解输出 “-1”。

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
<tr><td>3 3 2 3
...
...
...
3 3 2 3
...
...
X..
3 3 1 3
...
...
X..
11 11 4 6
......XX...
..X...XX..X
........X.X
...........
.......XX..
...X.....X.
.XX......X.
X....X...X.
.........X.
.X...XX....
...X.......</td><td>DD
DR
R
DDRR
</td></tr></table>


# Constraints



# Note

这是一道多case；
这是一道多case；
这是一道多case；

# Source


