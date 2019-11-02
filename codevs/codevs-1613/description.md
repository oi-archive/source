<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个地区中有n 个村庄，编号为1, 2, ..., n。有n – 1 条道路连接着这些村<br>庄，每条道路刚好连接两个村庄，从任何一个村庄，都可以通过这些道路到达其<br>他任一个村庄。每条道路的长度均为1 个单位。<br>为保证该地区的安全，巡警车每天要到所有的道路上巡逻。警察局设在编号<br>为1 的村庄里，每天巡警车总是从警察局出发，最终又回到警察局。<br>下图表示一个有8 个村庄的地区，其中村庄用圆表示（其中村庄1 用黑色的<br>圆表示），道路是连接这些圆的线段。为了遍历所有的道路，巡警车需要走的距<br>离为14 个单位，每条道路都需要经过两次。</p>
<p>为了减少总的巡逻距离，该地区准备在这些村庄之间建立K 条新的道路，<br>每条新道路可以连接任意两个村庄。两条新道路可以在同一个村庄会合或结束<br>（见下面的图例（c））。一条新道路甚至可以是一个环，即，其两端连接到同一<br>个村庄。<br>由于资金有限，K 只能是1 或2。同时，为了不浪费资金，每天巡警车必须<br>经过新建的道路正好一次。<br>下图给出了一些建立新道路的例子：</p>
<p>在(a)中，新建了一条道路，总的距离是11。在(b)中，新建了两条道路，总<br>的巡逻距离是10。在(c)中，新建了两条道路，但由于巡警车要经过每条新道路<br>正好一次，总的距离变为了15。<br>试编写一个程序，读取村庄间道路的信息和需要新建的道路数，计算出最佳<br>的新建道路的方案使得总的巡逻距离最小，并输出这个最小的巡逻距离。</p>
<p> </p>
<p> </p>

<img src="/source/codevs/codevs-1613/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNjEzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NDk2NTMyNS4wNDAuNDM4MjYzMDk0MTY2LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个整数n, K(1 ≤ K ≤ 2)。接下来n – 1 行，每行两个整数a, b，<br>表示村庄a 与b 之间有一条道路(1 ≤ a, b ≤ n)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，表示新建了K 条道路后能达到的最小巡逻距离。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】<br>8 1<br>1 2<br>3 1<br>3 4<br>5 3<br>7 5<br>8 5<br>5 6<br>【样例输入2】</p>
<p>8 2<br>1 2<br>3 1<br>3 4<br>5 3<br>7 5<br>8 5<br>5 6<br>【样例输入3】<br>5 2<br>1 2<br>2 3<br>3 4<br>4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【1】<br>11<br>【2】<br>10<br>【3】<br>6 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>10%的数据中，n ≤ 1000, K = 1；<br>30%的数据中，K = 1；<br>80%的数据中，每个村庄相邻的村庄数不超过25；<br>90%的数据中，每个村庄相邻的村庄数不超过150；<br>100%的数据中，3 ≤ n ≤ 100,000, 1 ≤ K ≤ 2。</p>
</div>
</div>