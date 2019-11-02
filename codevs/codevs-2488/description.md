<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　随着新版百度空间的上线，Blog宠物绿豆蛙完成了它的使命，去寻找它新的归宿。</span></p>
<p><span>　　<span>给出一个有向无环图，起点为1终点为N，每条边都有一个长度，并且从起点出发能够到达所有的点，所有的点也都能够到达终点。绿豆蛙从起点出发，走向终点。</span><br><span>　　到达每一个顶点时，如果有K条离开该点的道路，绿豆蛙可以选择任意一条道路离开该点，并且走向每条路的概率为 1/K 。</span><br><span>　　现在绿豆蛙想知道，从起点走到终点的所经过的路径总长度期望是多少？</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行: 两个整数 N M，代表图中有N个点、M条边</span><br><span>　　第二行到第 1+M 行: 每行3个整数 a b c，代表从a到b有一条长度为c的有向边</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　<span>从起点到终点路径总长度的期望值，四舍五入保留两位小数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4<br>1 2 1<br>1 3 2<br>2 3 3<br>3 4 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7.00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于20%的数据   N&lt;=100</span><br><span>　　对于40%的数据   N&lt;=1000</span><br><span>　　对于60%的数据   N&lt;=10000</span><br><span>　　对于100%的数据  N&lt;=100000，M&lt;=2*N</span></p>
<p><span><br></span></p>
<p><span>来源：Nescafe 19</span></p>
</div>
</div>