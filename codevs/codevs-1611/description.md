<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Siruseri 城中的道路都是单向的。不同的道路由路口连接。按照法律的规定，<br>在每个路口都设立了一个Siruseri 银行的ATM 取款机。令人奇怪的是，Siruseri<br>的酒吧也都设在路口，虽然并不是每个路口都设有酒吧。<br>Banditji 计划实施Siruseri 有史以来最惊天动地的ATM 抢劫。他将从市中心<br>出发，沿着单向道路行驶，抢劫所有他途径的ATM 机，最终他将在一个酒吧庆<br>祝他的胜利。<br>使用高超的黑客技术，他获知了每个ATM 机中可以掠取的现金数额。他希<br>望你帮助他计算从市中心出发最后到达某个酒吧时最多能抢劫的现金总数。他可<br>以经过同一路口或道路任意多次。但只要他抢劫过某个ATM 机后，该ATM 机<br>里面就不会再有钱了。<br>例如，假设该城中有6 个路口，道路的连接情况如下图所示：<br>市中心在路口1，由一个入口符号→来标识，那些有酒吧的路口用双圈来表<br>示。每个ATM 机中可取的钱数标在了路口的上方。在这个例子中，Banditji 能抢<br>劫的现金总数为47，实施的抢劫路线是：1-2-4-1-2-3-5。</p>

<img src="/source/codevs/codevs-1611/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNjExL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTYxMS5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个整数N、M。N 表示路口的个数，M 表示道路条数。接下来<br>M 行，每行两个整数，这两个整数都在1 到N 之间，第i+1 行的两个整数表示第<br>i 条道路的起点和终点的路口编号。接下来N 行，每行一个整数，按顺序表示每<br>个路口处的ATM 机中的钱数。接下来一行包含两个整数S、P，S 表示市中心的<br>编号，也就是出发的路口。P 表示酒吧数目。接下来的一行中有P 个整数，表示<br>P 个有酒吧的路口的编号。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，表示Banditji 从市中心开始到某个酒吧结束所能抢劫的最多<br />的现金总数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 7<br>1 2<br>2 3<br>3 5<br>2 4<br>4 1<br>2 6<br>6 5<br>10<br>12<br>8<br>16<br>1 5<br>1 4<br>4 3 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>47</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的输入保证N, M&lt;=3000。所有的输入保证N, M&lt;=500000。每个ATM<br>机中可取的钱数为一个非负整数且不超过4000。输入数据保证你可以从市中心<br>沿着Siruseri 的单向的道路到达其中的至少一个酒吧。</p>
</div>
</div>