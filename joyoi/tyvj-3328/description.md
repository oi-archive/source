# 

 
 # 题目描述 
<p>
【问题描述】<br>　　在一个5×5的棋盘上有12个白色的骑士和12个黑色的骑士， 且有一个空位。在任何时候一个骑士都能按照骑士的走法（它可以走到和它横坐标相差为1，纵坐标相差为2或者横坐标相差为2，纵坐标相差为1的格子）移动到空位上。<br>　　给定一个初始的棋盘，怎样才能经过移动变成如下目标棋盘：<br><br><center><img src="/source/joyoi/tyvj-3328/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMyOC9wcm9ibGVtc19pbWFnZXMvMjA5Ni8xLmJtcA==.bmp"></img></center>　<br>                           <br>　　为了体现出骑士精神，他们必须以最少的步数完成任务。<br></p> 

 
 # 输入格式 
<p>
Input Format<br>　　第一行有一个正整数T(T <= 10)，表示一共有N组数据。接下来有T个5×5的矩阵，0表示白色骑士，1表示黑色骑士，*表示空位。两组数据之间没有空行。<br></p> 

 
 # 输出格式 
<p>
Output Format<br>　　对于每组数据都输出一行。如果能在15步以内（包括15步）到达目标状态，则输出步数，否则输出－1。<br></p> 

 
 # 提示 
<p>
　　样例中第二个数据的初始情况对应该图：<br> <br><br><center><img src="/source/joyoi/tyvj-3328/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMyOC9wcm9ibGVtc19pbWFnZXMvMjA5Ni8yLmJtcA==.bmp"></img></center>　<br></p> 
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
10110
01*11
10111
01001
00000
01011
110*1
01110
01010
00100
</td><td>7
-1
</td></tr></table>
