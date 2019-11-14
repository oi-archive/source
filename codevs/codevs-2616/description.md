<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>政府计划建立一个大型的服务器中心，为各个城市提供网络服务。每个城市对网络的需求量是不一样的，而需求量越大，对线路的要求也就越高，线路的成本也就越高。因此需要选择合适的地点修建。每个城市用一个二维整数坐标表示，两个点之间的距离定义为水平距离＋垂直距离，即<span style="font-family: Consolas;">a,b</span><span style="">两点间距离为</span><span style="font-family: Consolas;">D(a,b)=|Xa-Xb|+|Ya-Yb|</span><span style="">。对于每个城市，线路的费用为：费用＝距离</span><span style="font-family: Consolas;">×</span><span style="">人口</span><span style="font-family: Consolas;">×</span><span style="">城市的网络需求程度。总的费用为各个城市的费用的总和。请你找出最适合安装服务器（既总费用最小）的整数坐标（不一定要在城市上）。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行有一个正整数<span style="font-family: Consolas;">N</span><span style="">（</span><span style="font-family: Consolas;">N ≤ 100000</span><span style="">），表示城市的数量。后面的</span><span style="font-family: Consolas;">n</span><span style="">行每行描述一个城市，每行有四个整数</span><span style="font-family: Consolas;">x</span><span style="">，</span><span style="font-family: Consolas;">y</span><span style="">，</span><span style="font-family: Consolas;">p</span><span style="">，</span><span style="font-family: Consolas;">k</span><span style="">分别表示城市的坐标，人口数，以及网络需求程度。（</span><span style="font-family: Consolas;">0 &lt; x, y &lt; 2^31</span><span style="">；</span><span style="font-family: Consolas;">p≤600, k ≤30</span><span style="">）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出包含一行。在这一行中，应当包含两个整数<span style="font-family: Consolas;">x</span><span style="font-family: 宋体;">，</span><span style="font-family: Consolas;">y</span><span style="font-family: 宋体;">表示最优解的坐标，如果有多个最优解，那么输出</span><span style="font-family: Consolas;">x</span><span style="font-family: 宋体;">最小的，如果有</span><span style="font-family: Consolas;">x</span><span style="font-family: 宋体;">相同，那么输出</span><span style="font-family: Consolas;">y</span><span style="font-family: 宋体;">最小的。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>2 3 5 3</p>
<p>2 1 100 30</p>
<p>2 2 1 1</p>
<p>3 2 7 6</p>
<p>1 1 4 30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N ≤ 100000</p>
<p>0 &lt; x, y &lt; 2^31<span style="">；</span><span style="font-family: Consolas;">p≤600, k ≤30</span></p>
</div>
</div>