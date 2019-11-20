# 

 
 # 题目描述 
<p>
One of the most popular attractions at the county fair is the<br>climbing wall. Bessie wants to plan her trip up the wall in advance<br>and needs your help.<br><br>The wall is 30,000 millimeters wide and H (1001 <= H <= 30,000)<br>millimeters high and has F (1 <= F <= 10,000) hoof-holds at unique<br>X,Y coordinates expressed in millimeters. 0,0 is at the ground level<br>on the left side of the wall. Hoof-holds are separated by at least<br>300 millimeters since no cow can maneuver them if they are spaced<br>too close! Bessie knows there is at least one way up.<br><br>Bessie, through techniques only she knows, uses successive single<br>hoof-holds to climb the wall. She can only move from one hoof-hold<br>to another if they are no more than one meter apart. She can, of<br>course, move up, down, right, left or some combination of these in<br>each move. Similarly, once she gets to a hoof-hold that is at least<br>H-1000 millimeters above the ground, she can nimbly climb from there<br>onto the platform atop the wall. Bessie can start at any X location<br>that has a Y location <= 1000 millimeters.<br><br>Given the height of the wall and the locations of the hoof-holds,<br>determine the smallest number of hoof-holds Bessie should use to<br>reach the top.<br><br>Bessie参加了爬墙比赛，比赛用的墙宽30000,高H(1001 <= H <= 30,000)。墙上有F(1 <= F <= 10,000)个不同的落脚点（X，Y）。 （0，0）在左下角的地面。所有的落脚点至少相距300。Bessie知道至少有一条路可以上去。<br>Bessie只能从一个落脚点爬到另一个距离不超过1000的落脚点，她可以向上下左右四个方向爬行。同样地，一旦她到达了一个高度 至少有H-1000的落脚点，她可以敏捷地爬到墙顶上。Bessie一开始可以在任意一个高度不超过1000的落脚点上。<br>问Bessie至少攀爬多少次.这里两个点的距离都是欧几里得距离</p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers, H and F.<br><br>* Lines 2..F+1: Each line contains two space-separated integers<br>        (respectively X and Y) that describe a hoof-hold. X is the<br>        distance from the left edge of the climbing wall; Y is the<br>        distance from the ground.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the smallest number of hoof-holds<br>        Bessie must use to reach the top of the climbing wall.<br><br></p> 
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
<tr><td>3000 5
600 800
1600 1800
100 1300
300 2100
1600 2300

INPUT DETAILS:

The wall is three meters high with 5 hoof-holds.
</td><td>3

OUTPUT DETAILS:

Bessie can start on the ground, move to the hoof-hold at (600,800), move
from there to (100,1300), move from there to (300,2100), and from that high
height can hop onto the platform. This trip requires three hoof-holds. 
There is no shorter path that Bessie can take.</td></tr></table>
