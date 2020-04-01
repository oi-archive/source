<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>在一个国家里，有n个城市（编号为0 到n-1）。这些城市之间有n条双向道 路相连（编号为0 到n-1），其中编号为i的道路连接了城市i和城市ri（一条道 路可以连接一个城市和它自身），长度为di。n 个城市中有m个拥有自己城堡， 可以抵御敌人侵略。如果没有城堡的城市遭受攻击，则离它最近的城堡将派兵前 往救援。 你的任务是在不超过k个没有城堡的城市中建立城堡，使得所有城市中“离 最近城堡的距离”的最大值尽量小。换句话说，若令dist(c)表示城市c的最近城 堡离它的距离，则你的任务是让max{dist(c)}尽量小。 输入数据保证存在方案使得对于每个城市，至少有一个城堡能够到达。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入第一行为三个正整数n, m, k。第二行包含n个整数r0,r1,…,rn-1。第三行 包含n 个整数d0,d1,…,dn-1。第四行包含m 个各不相同的0~n-1 之间的整数，分 别为m个城堡所在的城市编号。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出仅一行，包含一个整数，即max{dist(c)}的最小值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 3 3 <br>0 2 0 0 2 2 8 3 8 7 <br>10 9 1 8 1 3 7 2 8 1 <br>3 4 6</p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据满足：2&lt;=n&lt;=50, 1&lt;=di&lt;=106<br>, 0&lt;=m&lt;=n-k</p>
</div>
</div>