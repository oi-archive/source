
# Description

<div class="content"><p><span style="font-size: medium">布布是一个《泡泡堂》高手，拥有着近乎完美的战绩。他擅长很多地图，例如“小区10”、“海盗14”、“大海02”等等，不过他最喜欢的地图是“赛车”。<br/>
在赛车地图中，每个玩家将得到一辆赛车，从起点出发，比赛谁最先到达终点。<br/>
在地图中，包括有障碍、加油站、赛车跑道与沙地。障碍不可通过，并且赛车在赛车跑道与沙地上的行进速度是不一样的。</span></p>
<p><span style="font-size: medium">现在我们来考虑一个简化版的赛车游戏。在这个简化版本的赛车游戏中：<br/>
 比赛在一个无限大的沙地平面上举行。<br/>
 赛道是一个从原点出发、由n条线段首尾相接组成的折线。<br/>
 出于安全考虑，赛道不会自交（即折线中的任何两条线段，相邻两条线段有且仅有一个公共点，其他任意两条线段均无公共点）。<br/>
 赛车在赛道上的速度为va，在沙地上的速度为vb，且满足 。<br/>
 为了增加比赛的挑战性，在赛道上逆向行驶是允许的。</span></p>
<p><span style="font-size: medium">布布是一个操作非常精确的选手，他总能按照预想的道路行进至终点，但是他不知道哪个才是最快的路线，聪明的你，能帮助他么？<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第1行包含一个整数n，表示赛道一共有n段；第2行包含两个实数va与vb，分别表示赛车在赛道上与沙地中的行进速度。<br/>
接下来的n行，每行包含两个整数xi与yi，依次表示赛道的每一个转折点。即赛道的第一个线段是(0,0)(x1 , y1)，第二条线段是(x1 , y1) ( x2 , y2)，依次类推。其中(xn , yn)为终点。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">仅包含一个实数，表示从起点到终点最少所需时间。精确到小数点后6位。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
2<br/>
2 1<br/>
0 4<br/>
4 4<br/>
【样例输入2】<br/>
2<br/>
2 1<br/>
4 4<br/>
4 -4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
4.000000<br/>
<br/>
【样例输出2】<br/>
5.464102<br/>
<br/>
 <br/>
N&lt;=1000,1&lt;=Vb&lt;=Va&lt;=20<br/>
所有的坐标都在[-10^6 , 10^6]内。<br/>
<br/>
<br/>
当你的结果跟正确结果误差不超过0.0001时，即算通过</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

