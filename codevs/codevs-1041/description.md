<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>又到暑假了，住在城市A的Car想和朋友一起去城市B旅游。她知道每个城市都有四个飞机场，分别位于一个矩形的四个顶点上，同一个城市中两个机场之间有一条笔直的高速铁路，第I个城市中高速铁路了的单位里程价格为Ti，任意两个不同城市的机场之间均有航线，所有航线单位里程的价格均为t。</p>
<p>那么Car应如何安排到城市B的路线才能尽可能的节省花费呢?她发现这并不是一个简单的问题，于是她来向你请教。<br><strong>任务</strong><br>找出一条从城市A到B的旅游路线，出发和到达城市中的机场可以任意选取，要求总的花费最少。</p>

<img src="/source/codevs/codevs-1041/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMDQxL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMDQxLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个正整数n(0&lt;=n&lt;=10)，表示有n组测试数据。<br>每组的第一行有四个正整数s，t，A，B。<br>S(0&lt;S&lt;=100)表示城市的个数，t表示飞机单位里程的价格，A，B分别为城市A，B的序号，(1&lt;=A，B&lt;=S)。<br>接下来有S行，其中第I行均有7个正整数xi1，yi1，xi2，yi2，xi3，yi3，Ti，这当中的(xi1，yi1)，(xi2，yi2)，(xi3，yi3)分别是第I个城市中任意三个机场的坐标，T I为第I个城市高速铁路单位里程的价格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共有n行，每行一个数据对应测试数据。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br>3 10 1 3<br>1 1 1 3 3 1 30<br>2 5 7 4 5 2 1<br>8 6 8 8 11 6 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>47.5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如描述</p>
</div>
</div>