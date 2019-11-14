
# Description

<div class="content"><div>小Q设计了一款2D游戏，它的地图建立在二维笛卡尔坐标系上。这个游戏最大的特色就是可以随机生成地图，但是</div>
<div>岛屿生成却给小Q带来了巨大的麻烦。一个岛屿可以看成一个恰好有n个顶点的简单多边形，每个顶点的坐标都必须</div>
<div>是整数，同时为了防止精度误差，每条边的长度也必须是整数。为了体现程序的随机性，任何一条边都不能与x轴</div>
<div>或者y轴平行。当然，这个多边形不能自交，也不允许连续3个点共线。请写一个程序帮助小Q实现岛屿生成功能。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(3&lt;=n&lt;=1000)，表示多边形的点数。</div>
<div></div></div>

# Output

<div class="content"><div>输出n行，每行两个整数x_i,y_i(|x_i|,|y_i|&lt;=10000)，按顺时针或者逆时针顺序依次输出每个顶点的坐标。</div>
<div>若有多组解，输出任意一组。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 0<br/>
4 3<br/>
-20 21</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

