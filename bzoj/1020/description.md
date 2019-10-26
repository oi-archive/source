
# Description

<div class="content"><p>　　在设计航线的时候，安全是一个很重要的问题。首先，最重要的是应采取一切措施确保飞行不会发生任何事故<br/>
，但同时也需要做好最坏的打算，一旦事故发生，就要确保乘客有尽量高的生还几率。当飞机迫降到海上的时候，<br/>
最近的陆地就是一个关键的因素。航线中最危险的地方就是距离最近的陆地最远的地方，我们称这种点为这条航线<br/>
“孤地点”。孤地点到最近陆地的距离被称为“孤地距离”。作为航空公司的高级顾问，你接受的第一个任务就是<br/>
尽量找出一条航线的孤地点，并计算这条航线的孤地距离。为了简化问题，我们认为地图是一个二维平面，陆地可<br/>
以用多边形近似，飞行线路为一条折线。航线的起点和终点都在陆地上，但中间的转折点是可能在海上（如下图所<br/>
示，方格标示出了孤地点）。</p>
<p><span style="font-size: medium"><img border="0" alt="" src="/source/bzoj/1020/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEwMjAvMS5qcGc=.jpg"/> </span></p></div>

# Input

<div class="content"><p>　　输入的第一行包括两个整数C和N（1≤C≤20，2≤N≤20），分别代表陆地的数目的航线的转折点的数目。接下<br/>
来有N行，每行有两个整数x,y。(x,y)表示一个航线转折点的坐标，第一个转折点为航线的起点，最后一个转折点<br/>
为航线的终点。接下来的输入将用来描述C块大陆。每块输入由一个正整数M开始（M≤30），M表示多边形的顶点个<br/>
数，接下来的M行，每行会包含两个整数x,y，(x,y)表示多边形的一个顶点坐标，我们保证这些顶点以顺时针或逆<br/>
时针给出了该多边形的闭包，不会出现某些边相交的情况。此外我们也保证输入数据中任何两块大陆不会相交。输<br/>
入的所有坐标将保证在-10000到10000的范围之间。</p></div>

# Output

<div class="content"><p>　　输出一个浮点数，表示航线的孤地距离，数据保留2位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 2<br/>
-9 -6<br/>
5 1<br/>
3<br/>
0 16<br/>
-16 -12<br/>
17 -6	</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.00</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=NWERC 2007">NWERC 2007</a></p></div>

