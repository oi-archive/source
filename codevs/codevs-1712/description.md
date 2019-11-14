<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>众所周知，我们可以通过直角坐标系把平面上的任何一个点 P 用一个有序数对 (x,y)来唯一表示，如果 x,y 都是整数，我们就把点 P 称为整点，否则点 P 称为 非整点。我们把平面上所有整点构成的集合记为 W。 <br>定义 1 两个整点 P1(x1,y1),P2(x2,y2)，若|x1-x2|+|y1-y2|=1，则称 P1,P2相邻，记作 P1~P2，否则称 P1,P2不相邻。 <br>定义 2 设点集 S 是 W 的一个有限子集，即 S={P1,P2,…,Pn}(n&gt;=1)，其中 Pi(1&lt;=i&lt;=n)属于 W，我们把 S 称为整点集。 <br>定义 3 设 S 是一个整点集，若点 R,T 属于 S，且存在一个有限的点序列 Q1,Q2,…,Qk满足: <br>1. Qi属于 S（1&lt;=i&lt;=k）; 2. Q1=R,Qk= T; 3. Qi~Qi+1(1&lt;=i&lt;=k-1)，即 Qi与 Qi+1相邻; 4. 对于任何 1&lt;=i&lt;j&lt;=k 有 Qi≠Qj; <br>我们则称点 R 与点 T 在整点集 S 上连通，把点序列 Q1,Q2,…,Qk称为整点集 S 中 连接点 R 与点 T 的一条道路。 <br>定义 4 若整点集 V 满足：对于 V 中的任何两个整点，V 中有且仅有一条连接这 两点的道路，则 V 称为单整点集。 <br>定义 5 对于平面上的每一个整点，我们可以赋予它一个整数，作为该点的权， 于是我们把一个整点集中所有点的权的总和称为该整点集的权和。 <br>我们希望对于给定的一个单整点集 V，求出一个 V 的最优连通子集 B，满足： <br>1. B 是 V 的子集 2. 对于 B 中的任何两个整点，在 B 中连通； 3. B 是满足条件(1)和(2)的所有整点集中权和最大的。 <br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行是一个整数 N，表示单整点集 V 中点的个数； <br>以下 N 行中，第 i 行(1&lt;=i&lt;=N)有三个整数，Xi,Yi,Ci依次表示第 i 个点的横坐 标，纵坐标和权。同一行相邻两数之间用一个空格分隔。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一个整数，表示所求最优连通集的权和。</p>

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
<p>0 0 –2</p>
<p>0 1 1</p>
<p>1 0 1</p>
<p>0 –1 1</p>
<p>-1 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2&lt;=N&lt;=1000 -10^6&lt;=Xi,Yi&lt;=10^6 -100&lt;=Ci&lt;=100 </p>
</div>
</div>