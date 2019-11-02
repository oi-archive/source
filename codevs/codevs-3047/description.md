<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小T打算在城市C开设一家外送快餐店。送餐到某一个地点的时间与外卖店到该地点之间最短路径长度是成正比的，小T希望快餐店的地址选在离最远的顾客距离最近的地方。<br> <br> 快餐店的顾客分布在城市C的N 个建筑中，这N  个建筑通过恰好N  条双向道路连接起来，不存在任何两条道路连接了相同的两个建筑。任意两个建筑之间至少存在一条由双向道路连接而成 的路径。小T的快餐店可以开设在任一建筑中，也可以开设在任意一条道路的某个位置上（该位置与道路两端的建筑的距离不一定是整数）。<br> <br> 现给定城市C的地图（道路分布及其长度），请找出最佳的快餐店选址，输出其与最远的顾客之间的距离。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括一个整数n表示城市C中建筑物与道路的数目</p>
<p>接下来N行，每行包括三个整数Ai，Bi，Li（1&lt;=i&lt;=n,Li&gt;0)表示一条道路连接了Ai，Bi，其长度为Li</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅为一个实数四舍五入保留恰好一位小数表示最佳快餐店选址离最远用户的距离</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】<br> 4 <br> 1 2 1 <br> 1 4 2 <br> 1 3 2 <br> 2 4 1<br> 【样例输入2】<br> 5<br> 1 5 100<br> 2 1 77<br> 3 2 80<br> 4 1 64<br> 5 3 41</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】<br> 2.0 <br> 【样例输出2】<br> 109.0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例1<br> <img src="/source/codevs/codevs-3047/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zMDQ3L2h0dHA6Ly9vai5sdW9ndS5vcmc6ODg4OC91c2Vyc2V0L2dldHBpYy5waHA_cGljaWQ9MjAy.php"><br> 样例2<br> <img src="/source/codevs/codevs-3047/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zMDQ3L2h0dHA6Ly9vai5sdW9ndS5vcmc6ODg4OC91c2Vyc2V0L2dldHBpYy5waHA_cGljaWQ9MjAz.php"><br> 数据范围<br> 对于 10%的数据，N&lt;=80,Li=1； <br> 对于 30%的数据，N&lt;=600，Li&lt;=100； <br> 对于 60% 的数据，N&lt;=2000，Li&lt;=10^9； <br> 对于 100% 的数据，N&lt;=10^5，Li&lt;=10^9</p>
</div>
</div>