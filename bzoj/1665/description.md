
# Description

<div class="content"><p><span style="font-size: medium">One of the most popular attractions at the county fair is the climbing wall. Bessie wants to plan her trip up the wall in advance and needs your help. The wall is 30,000 millimeters wide and H (1001 &lt;= H &lt;= 30,000) millimeters high and has F (1 &lt;= F &lt;= 10,000) hoof-holds at unique X,Y coordinates expressed in millimeters. 0,0 is at the ground level on the left side of the wall. Hoof-holds are separated by at least 300 millimeters since no cow can maneuver them if they are spaced too close! Bessie knows there is at least one way up. Bessie, through techniques only she knows, uses successive single hoof-holds to climb the wall. She can only move from one hoof-hold to another if they are no more than one meter apart. She can, of course, move up, down, right, left or some combination of these in each move. Similarly, once she gets to a hoof-hold that is at least H-1000 millimeters above the ground, she can nimbly climb from there onto the platform atop the wall. Bessie can start at any X location that has a Y location &lt;= 1000 millimeters. Given the height of the wall and the locations of the hoof-holds, determine the smallest number of hoof-holds Bessie should use to reach the top.</span></p>
<p><span style="font-size: medium"> </span></p>
<p><span style="font-size: medium">Bessie参加了爬墙比赛，比赛用的墙宽30000,高H(1001 &lt;= H &lt;= 30,000)。墙上有F(1 &lt;= F &lt;= 10,000)个不同的落脚点（X，Y）。 （0，0）在左下角的地面。所有的落脚点至少相距300。Bessie知道至少有一条路可以上去。 Bessie只能从一个落脚点爬到另一个距离不超过1000的落脚点，她可以向上下左右四个方向爬行。同样地，一旦她到达了一个高度 至少有H-1000的落脚点，她可以敏捷地爬到墙顶上。Bessie一开始可以在任意一个高度不超过1000的落脚点上。问Bessie至少攀爬多少次.这里两个点的距离都是欧几里得距离</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers, H and F. </span></p>
<p><span style="font-size: medium">* Lines 2..F+1: Each line contains two space-separated integers (respectively X and Y) that describe a hoof-hold. X is the distance from the left edge of the climbing wall; Y is the distance from the ground.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer that is the smallest number of hoof-holds Bessie must use to reach the top of the climbing wall. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3000 5<br/>
600 800<br/>
1600 1800<br/>
100 1300<br/>
300 2100<br/>
1600 2300<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
The wall is three meters high with 5 hoof-holds.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: medium"> 分别经过(600,800), (100,1300), (300,2100)</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver
">Silver<br/>
</a></p></div>

