<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　在一个N * M的棋盘上，摆放着K个棋子，一个棋子占据一个格子(可能有多个棋子占据同一个格子)，控制棋盘上所有与它相距不超过R的格子。两个格子(X1,Y1)、(X2,Y2)间的距离定义为|X1-X2|+|Y1-Y2|。</p>
<p>　　试设计一个算法，计算出K个棋子控制的格子总数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　第一行共三个正整数N，M，K。</p>
<p>   以下K行，每行三个正整数X，Y，R，分别表示棋子的所在行，所在列和控制范围。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　共一个数，即控制的格子总数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4 3</p>
<p>1 1 1</p>
<p>3 1 1</p>
<p>3 3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>在 15% 的数据中，1≤N,M≤1000，1≤K≤100</p>
<p>在 25% 的数据中，1≤N,M≤5000，1≤K≤100</p>
<p>在 35% 的数据中，1≤N,M≤10000，1≤K≤100</p>
<p>在 50% 的数据中，1≤N,M≤100000，1≤K≤100</p>
<p>在 65% 的数据中，1≤N,M≤100000000，1≤K≤100</p>
<p>在 80% 的数据中，1≤N,M≤100000000，1≤K≤1000</p>
<p>在 100% 的数据中，1≤N,M≤100000000，1≤K≤100000</p>
</div>
</div>