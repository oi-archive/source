<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在设计航线的时候，安全是一个很重要的问题。首先，最重要的是应采取一切措施确保飞行不会发生任何事故，但同时也需要做好最坏的打算，一旦事故发生，就要确保乘客有尽量高的生还几率。</p>
<p>当飞机迫降到海上的时候，最近的陆地就是一个关键的因素。航线中最危险的地方就是距离最近的陆地最远的地方，我们称这种点为这条航线“孤地点”。孤地点到最近陆地的距离被称为“孤地距离”。作为航空公司的高级顾问，你接受的第一个任务就是尽量找出一条航线的孤地点，并计算这条航线的孤地距离。</p>
<p><br> 为了简化问题，我们认为地图是一个二维平面，陆地可以用多边形近似，飞行线路为一条折线。航线的起点和终点都在陆地上，但中间的转折点是可能在海上</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包括两个整数C和N（1≤C≤20，2≤N≤20），分别代表陆地的数目的航线的转折点的数目。</p>
<p>接下来有N行，每行有两个整数x,y。(x,y)表示一个航线转折点的坐标，第一个转折点为航线的起点，最后一个转折点为航线的终点。</p>
<p>接下来的输入将用来描述C块大陆。每块输入由一个正整数M开始（M≤30），M表示多边形的顶点个数，接下来的M行，每行会包含两个整数x,y，(x,y)表示多边形的一个顶点坐标，我们保证这些顶点以顺时针或逆时针给出了该多边形的闭包，不会出现某些边相交的情况。此外我们也保证输入数据中任何两块大陆不会相交。</p>
<p>输入的所有坐标将保证在-10000到10000的范围之间。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个浮点数，表示航线的孤地距离，数据保留2位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3</p>
<p>12 4</p>
<p>16 17</p>
<p>3 9</p>
<p>4</p>
<p>1 0</p>
<p>4 19</p>
<p>19 14</p>
<p>6 12</p>
<p>3</p>
<p>10 10</p>
<p>5 3</p>
<p>18 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2.94</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤C≤20，2≤N≤20</p>
<p>所有坐标将保证在-10000到10000的范围之间</p>
</div>
</div>