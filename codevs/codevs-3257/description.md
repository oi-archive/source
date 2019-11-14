<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>经过多年的生产经营，农场主 John 现在运营着 N(1 ≤ N ≤ 100)个农场构成的生产 网络。 农场 i 的位置用(x_i, y_i)二维坐标来描述， 不同的农场保证坐标位置不同且 x_i, y_i 都是整数。 农场主 John 想请你帮助他计划每天给 N 个农场供货的配送路线，从农场 1 出发，他计 划有序的访问所有的农场（即从农场 1 到农场 2， 然后再到农场 3 等等） 。 最后在访问完农场 N 后要返回农场 1，John 每分钟只能朝一个方向行走一个单位距离（东西南北四个方向任意 选择） ， 并且 John 还要求整个行程中除了农场 1， 其他所有农场只访问 1 次 （农场 1 也只能 访问 2 次） 。</p>
<p>请你帮 John 计算出整个配送路线的最少时间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个整数 N，表示农场的数量。</p>
<p>第 2 行到第 N+1 行，每行两个用空格隔开的整数 x_i 和  y_i  (1≤ x_i, y_i ≤ 1,000,000)。表示农场 i 的坐标。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数，表示整个配送路线的最少时间。如果不存在满足要求的路线则输出-1</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>2 2</p>
<p>2 4</p>
<p>2 1</p>
<p>1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>题目当中已经说清楚了</p>
</div>
</div>