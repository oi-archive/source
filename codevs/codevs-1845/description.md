<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>已知一棵特殊的二叉查找树。根据定义，该二叉查找树中每个结点的数据值都比它左儿子结点的数据值大，而比它右儿子结点的数据值小。</p><p>另一方面，这棵查找树中每个结点都有一个权值，每个结点的权值都比它的儿子结点的权值要小。</p><p>已知树中所有结点的数据值各不相同；所有结点的权值也各不相同。这时可得出这样一个有趣的结论：如果能够确定树中每个结点的数据值和权值，那么树的形态便可以唯一确定。因为这样的一棵树可以看成是按照权值从小到大顺序插入结点所得到的、按照数据值排序的二叉查找树。</p><p>一个结点在树中的深度定义为它到树根的距离加1。因此树的根结点的深度为1。</p><p>每个结点除了数据值和权值以外，还有一个访问频度。我们定义一个结点在树中的访问代价为它的访问频度乘以它在树中的深度。整棵树的访问代价定义为所有结点在树中的访问代价之和。</p><p>现在给定每个结点的数据值、权值和访问频度，你可以根据需要修改某些结点的权值，但每次修改你会付出K的额外修改代价。你可以把结点的权值改为任何实数，但是修改后所有结点的权值必须仍保持互不相同。现在你要解决的问题是，整棵树的访问代价与额外修改代价的和最小是多少？</p>

<img src="/source/codevs/codevs-1845/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xODQ1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTg0NS5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中的第一行为两个正整数N，K。其中：N表示结点的个数，K表示每次修改所需的额外修改代价。</p><p>接下来的一行为N个非负整数，表示每个结点的数据值。</p><p>再接下来的一行为N个非负整数，表示每个结点的权值。</p><p>再接下来的一行为N个非负整数，表示每个结点的访问频度。</p><p>其中：所有的数据值、权值、访问频度均不超过400000。每两个数之间都有一个空格分隔，且行尾没有空格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件中仅一行为一个数，即你所能得到的整棵树的访问代价与额外修改代价之和的最小值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 10</p><p>1 2 3 4</p><p>1 2 3 4</p><p>1 2 3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>29</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p><p>输入的原图是左图，它的访问代价是：1&amp;times;1+2&amp;times;2+3&amp;times;3+4&amp;times;4=30。</p><p>最佳的修改方案是把输入中的第3个结点的权值改成0，得到上图，访问代价是：1&amp;times;2+2&amp;times;3+3&amp;times;1+4&amp;times;2=19，加上额外修改代价10，一共是29。</p><p> </p><p>【数据规模和约定】</p><p>对于40%的数据，满足：N&lt;=30；</p><p>对于70%的数据，满足：N&lt;=50；</p><p>对于100%的数据，满足：N&lt;=70，1&lt;=K&lt;=30000000。</p>
</div>
</div>