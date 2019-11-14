
# Description

<div class="content"><p><span style="font-size: medium">一个直径为1/2的小球，在一个N×m的网格里面运动。<br/>
。小球运动的初始方向Xv，Yv∈{-1，0，1）。<br/>
在横向和纵向都有一些光线，问f时刻小球会碰到多少次光线。碰到两条光线的交点只计算一次。<br/>
询问次数&lt;=10000．n，m&lt;=100000</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">The first line of the standard input contains two integers n and m (1&lt;=N,M&lt;=100000) that represent the dimensions of the table. The second line contains an  -character word composed of the digits 0 i 1. The  -th letter of the word describes the state of the  -th horizontal transmitter where 0 means that the transmitter is off and 1 means that it is on. The third line contains an M-character word that describes the state of the vertical transmitters. <br/>
The fourth line of the input contains an integer k(1&lt;=K&lt;=10000)): the number of queries. Each of the following K lines contains five integers x,y,Xv,Yv,t(1&lt;x&lt;M,1&lt;y&lt;N,Xv,Yv属于[-1,1],1&lt;=T&lt;=10^9) that describe the initial position, the velocity of the ball and the duration of its movement. <br/>
</span></p></div>

# Output

<div class="content"><p><font size="4">Your program should output exactly k lines to the standard output: the answers to the respective queries. Each answer should have the form of a single integer: the number of times the hit signal was displayed. </font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 6<br/>
1010<br/>
010110<br/>
1<br/>
5 2 1 1 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><p><img height="232" width="332" alt="" src="/source/bzoj/3490/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMy9mZi5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

