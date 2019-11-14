<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个送外卖的，他手上有n份订单，他要把n份东西，分别送达n个不同的客户的手上。n个不同的客户分别在1~n个编号的城市中。送外卖的从0号城市出发，然后n个城市都要走一次（一个城市可以走多次），最后还要回到0点（他的单位），请问最短时间是多少。现在已知任意两个城市的直接通路的时间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数n （1&lt;=n&lt;=15）</p>
<p>接下来是一个（n+1）*(n+1)的矩阵，矩阵中的数均为不超过10000的正整数。矩阵的i行j列表示第i-1号城市和j-1号城市之间直接通路的时间。当然城市a到城市b的直接通路时间和城市b到城市a的直接通路时间不一定相同，也就是说道路都是单向的。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个正整数表示最少花费的时间</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>3
0 1 10 10
1 0 1 2
10 1 0 10
10 2 10 0</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=15</p>
</div>
</div>