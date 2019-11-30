<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Morenan被困在了一个迷宫里。迷宫可以视为N个点M条边的有向图，其中Morenan处于起点S，迷宫的终点设为T。可惜的是，Morenan非常的脑小，<strong>他只会从一个点出发随机沿着一条从该点出发的有向边，到达另一个点。</strong>这样，Morenan走的步数可能很长，也可能是无限，更可能到不了终点。<strong>若到不了终点，则步数视为无穷大。</strong>但你必须想方设法求出Morenan所走步数的期望值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行4个整数，N,M,S,T</p>
<p>第[2, M+1]行每行两个整数o1, o2，表示有一条从o1到o2的边。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">一个浮点数，保留小数点3位，为步数的期望值。若期望值为无穷大，则输出"INF"。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 6 1 6</p>
<p>1 2</p>
<p>1 3</p>
<p>2 4</p>
<p>3 5</p>
<p>4 6</p>
<p>5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3.000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=10000</p>
<p>M&lt;=1000000</p>
<p>保证强连通分量的大小不超过100</p>
</div>
</div>