<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【问题描述】<br>设 T=(V, E, W) 是一个无圈且连通的无向图（也称为无根树），每条边带有正整数的权，我<br>们称T 为树网（treenetwork），其中V, E分别表示结点与边的集合，W 表示各边长度的集合，<br>并设T 有n个结点。<br>路径：树网中任何两结点a,b 都存在唯一的一条简单路径，用d(a,b)表示以a,b 为端点的<br>路径的长度，它是该路径上各边长度之和。我们称d(a,b)为a,b 两结点间的距离。<br>一点v到一条路径P的距离为该点与P 上的最近的结点的距离：<br>d(v，P)=min{d(v，u)，u 为路径P 上的结点}。<br>树网的直径：树网中最长的路径称为树网的直径。对于给定的树网T，直径不一定是唯一的，<br>但可以证明：各直径的中点（不一定恰好是某个结点，可能在某条边的内部）是唯一的，我们称该<br>点为树网的中心。<br>偏心距 ECC(F)：树网T 中距路径F 最远的结点到路径F 的距离，即<br>ECC(F ) = max{d(v, F ), vÎV}。<br>任务：对于给定的树网T=(V, E,W)和非负整数s，求一个路径F，它是某直径上的一段路径<br>（该路径两端均为树网中的结点），其长度不超过s（可以等于s），使偏心距ECC(F)最小。我们<br>称这个路径为树网T=(V,E,W)的核（Core）。必要时，F 可以退化为某个结点。一般来说，在上<br>述定义下，核不一定只有一个，但最小偏心距是唯一的。<br>下面的图给出了树网的一个实例。图中，A-B 与A-C是两条直径，长度均为20。点W是树网<br>的中心，EF边的长度为5。如果指定s=11，则树网的核为路径DEFG（也可以取为路径DEF），偏<br>心距为8。如果指定s=0（或s=1、s=2），则树网的核为结点F，偏心距为12。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1 行，两个正整数n和s，中间用一个空格隔开。其中n 为树网结点的个数，s为树网的核<br>的长度的上界。设结点编号依次为1, 2, ..., n。<br>从第2 行到第n行，每行给出3 个用空格隔开的正整数，依次表示每一条边的两个端点编号和<br>长度。例如，“2 4 7”表示连接结点2 与4 的边的长度为7。</p>
<p>所给的数据都是正确的，不必检验。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一个非负整数，为指定意义下的最小偏心距</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例1】<br>5 2<br>1 2 5<br>2 3 2<br>2 4 4<br>2 5 3</p>
<p>【输入样例2】<br>8 6<br>1 3 2<br>2 3 2<br>3 4 6<br>4 5 3<br>4 6 4<br>4 7 2<br>7 8 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例1】</p>
<p>5</p>
<p>【输出样例1】</p>
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【限制】<br>40%的数据满足：5&lt;=n&lt;=15<br>70%的数据满足：5&lt;=n&lt;=80<br>100%的数据满足：5&lt;=n&lt;=300, 0&lt;=s&lt;=1000。边长度为不超过1000 的正整数</p>
</div>
</div>