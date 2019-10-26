
# Description

<div class="content"><p>聪聪研究发现，荒岛野人总是过着群居的生活，但是，并不是整个荒岛上的所有野人都属于同一个部落，野人们总是拉帮结派形成属于自己的部落，不同的部落之间则经常发生争斗。只是，这一切都成为谜团了——聪聪根本就不知道部落究竟是如何分布的。  不过好消息是，聪聪得到了一份荒岛的地图。地图上标注了N个野人居住的地点（可以看作是平面上的坐标）。我们知道，同一个部落的野人总是生活在附近。我们把两个部落的距离，定义为部落中距离最近的那两个居住点的距离。聪聪还获得了一个有意义的信息——这些野人总共被分为了K个部落！这真是个好消息。聪聪希望从这些信息里挖掘出所有部落的详细信息。他正在尝试这样一种算法：  对于任意一种部落划分的方法，都能够求出两个部落之间的距离，聪聪希望求出一种部落划分的方法，使靠得最近的两个部落尽可能远离。 例如，下面的左图表示了一个好的划分，而右图则不是。请你编程帮助聪聪解决这个难题。   <img border="0" src="/source/bzoj/1821/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4MjEuanBn.jpg" alt=""/></p></div>

# Input

<div class="content"><div>第一行包含两个整数N和K(1&lt; = N &lt; = 1000,1&lt; K &lt; = N)，分别代表了野人居住点的数量和部落的数量。</div>
<div>接下来N行，每行包含两个正整数x,y，描述了一个居住点的坐标(0 &lt; =x, y &lt; =10000)</div></div>

# Output

<div class="content"><p>输出一行，为最优划分时，最近的两个部落的距离，精确到小数点后两位。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
0 0<br/>
0 1<br/>
1 1<br/>
1 0	<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.00<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JSOI2010第二轮Contest1">JSOI2010第二轮Contest1</a></p></div>

