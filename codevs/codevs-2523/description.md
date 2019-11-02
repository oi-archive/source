<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在野外训练中，为了确保每位参加集训的成员安全，实时的掌握和收集周边<br>环境和队员信息非常重要， 集训队采用的方式是在训练所在地散布 N 个小型传感<br>器来收集并传递信息，这些传感器只与设在集训地中的信号塔进行通信，信号塔<br>接收信号的覆盖范围是圆形， 可以接收到所有分布在该集训区域内所有 N 个小型<br>传感器（包括在该圆形的边上）发出的信号。信号塔的功率与信号塔接收范围半<br>径的大小成正比，因为是野外训练，只能使用事先储备好的蓄电设备，因此在可<br>以收集所有传感器信息的基础上，还应使得信号塔的功率最小。小龙帮助教官确<br>定了一种信号塔设置的方案，既可以收集到所有 N 个传感器的信号，又可以保证<br>这个信号塔的功率是最小的。同学们，你们知道，这个信号塔的信号收集半径有<br>多大，它应该设置在何处吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共 N+1 行，第一行为正整数 N（1≤N≤1000000） ，表示队员个数。接下来<br>N 行，每行两个实数用空格分开，分别是第 i 个队员的坐标 Xi和Yi（Xi，<br>Yi 不超过双精度范围） 。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，共三个实数（中间用空格隔开） ，分别是信号塔的坐标，和信号塔<br />覆盖的半径。</p>

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
<p>1.200 1.200</p>
<p>2.400 2.400</p>
<p>3.800 4.500</p>
<p>2.500 3.100</p>
<p>3.900 1.300</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2.50 2.85 2.10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据 1≤N≤10000</p>
<p>70%的数据 1≤N≤200000</p>
<p>100%的数据 1≤N≤500000</p>
</div>
</div>