<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　红黑树是一类特殊的二叉搜索树，其中每个结点被染成红色或黑色。若将二叉搜索树结点中的空指针看作是指向一个空结点，则称这类空结点为二叉搜索树的前端结点。并规定所有前端结点的高度为-1。</p>
<p>　　一棵红黑树是满足下面“红黑性质”的染色二叉搜索树：</p>
<p>　　(1) 每个结点被染成红色或黑色；</p>
<p>　　(2) 每个前端结点为黑色结点；</p>
<p>　　(3) 任一红结点的子结点均为黑结点；</p>
<p>　　(4) 在从任一结点到其子孙前端结点的所有路径上具有相同的黑结点数。</p>
<p>　　从红黑树中任一结点x出发(不包括结点x)，到达一个前端结点的任意一条路径上的黑结点个数称为结点x的黑高度，记作bh(x)。红黑树的黑高度定义为其根结点的黑高度。</p>
<p>　　给定正整数N，试设计一个算法，计算出在所有含有N个结点的红黑树中，红色内结点个数的最小值和最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　输入共一个数N。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　输出共两行。</p>
<p>　　第一行为红色内结点个数的最小值，第二行为最大值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30% 的数据，1≤N≤100</p>
<p>对于 60% 的数据，1≤N≤1000</p>
<p>对于 100% 的数据，1≤N≤5000</p>
</div>
</div>