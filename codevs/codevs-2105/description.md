<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这里有一辆赛车比赛正在进行，赛场上一共有N辆车，分别称为个g1，g2……gn。赛道是一条无限长的直线。最初，gi位于距离起跑线前进ki的位置。比赛开始后，车辆gi将会以vi单位每秒的恒定速度行驶。在这个比赛过程中，如果一辆赛车曾经处于领跑位置的话（即没有其他的赛车跑在他的前面），这辆赛车最后就可以得奖，而且比赛过程中不用担心相撞的问题。现在给出所有赛车的起始位置和速度，你的任务就是算出那些赛车将会得奖。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有一个正整数N表示赛车的个数。</p>
<p>接下来一行给出N个整数，按顺序给出N辆赛车的起始位置。</p>
<p>再接下来一行给出N个整数，按顺序给出N辆赛车的恒定速度。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包括两行，第一行为获奖的赛车个数。</p>
<p>第二行按从小到大的顺序输出获奖赛车的编号，编号之间用空格隔开，注意最后一个编号后面不要加空格。</p>
<p>&nbsp;</p>

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
<p>1 1 0 0</p>
<p>15 16 10 20</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，N&lt;=10</p>
<p>对于50%的数据，N&lt;=6000</p>
<p>对于100%的数据N&lt;=10000, 0&lt;=ki&lt;=10^9, 0&lt;=vi&lt;=10^9</p>
</div>
</div>