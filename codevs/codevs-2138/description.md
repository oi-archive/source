<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一棵N个节点的树，去掉这棵树的一条边需要消耗值1，为这个图的两个点加上一条边也需要消耗值1。树的节点编号从1开始。在这个问题中，你需要使用最小的消耗值（加边和删边操作）将这棵树转化为环，不允许有重边。</p>
<p>环的定义如下：</p>
<p>（1）该图有N个点，N条边。</p>
<p>（2）每个顶点的度数为2。</p>
<p>（3）任意两点是可达的。</p>
<p>树的定义如下：</p>
<p>（1）该图有N个点，N-1条边。</p>
<p>（2）任意两点是可达的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个整数N代表节点的个数。</p>
<p>接下来N-1行每行有两个整数U, V（1 ≤ U, V ≤ N），表示双向边（U, V）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出把树转化为环的最小消耗值。</p>
<p><strong>&nbsp;</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<p>4</p>
<p>1 2</p>
<p>2 3</p>
<p>2 4</p>
</div>

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
<div>
<p>对于20%的数据，有1≤<em>N</em>≤10。</p>
<p>       对于100%的数据，有1≤<em>N</em>≤1000000</p>
</div>
</div>
</div>