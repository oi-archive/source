<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在农夫约翰的农场上，每逢下雨，Bessie最喜欢的三叶草地就积聚了一潭水。这意味着草地被水淹没了，并且小草要继续生长还要花相当长一段时间。因此，农夫约翰修建了一套排水系统来使贝茜的草地免除被大水淹没的烦恼（不用担心，雨水会流向附近的一条小溪）。作为一名一流的技师，农夫约翰已经在每条排水沟的一端安上了控制器，这样他可以控制流入排水沟的水流量。</p>
<p>农夫约翰知道每一条排水沟每分钟可以流过的水量，和排水系统的准确布局（起点为水潭而终点为小溪的一张网）。需要注意的是，有些时候从一处到另一处不只有一条排水沟。</p>
<p>根据这些信息，计算从水潭排水到小溪的最大流量。对于给出的每条排水沟，雨水只能沿着一个方向流动，注意可能会出现雨水环形流动的情形。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行: 两个用空格分开的整数N (0 &lt;= N &lt;= 200) 和 M (2 &lt;= M &lt;= 200)。N是农夫John已经挖好的排水沟的数量，M是排水沟交叉点的数量。交点1是水潭，交点M是小溪。</p>
<p>第二行到第N+1行: 每行有三个整数，Si, Ei, 和 Ci。Si 和 Ei (1 &lt;= Si, Ei &lt;= M) 指明排水沟两端的交点，雨水从Si 流向Ei。Ci (0 &lt;= Ci &lt;= 10,000,000)是这条排水沟的最大容量。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出一个整数，即排水的最大流量。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5 4
1 2 40
1 4 20
2 4 20
2 3 30
3 4 10</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>50</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>