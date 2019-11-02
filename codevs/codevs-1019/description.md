<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       集合论与图论对于小松来说是比数字逻辑轻松，比数据结构难的一门专业必修课。虽然小松在高中的时候已经自学过了离散数学中的图论，组合，群论等知识。但对于集合论，小松还是比较陌生的。集合论的好多东西也涉及到了图论的知识。</p>
<p> </p>
<p>       在第四讲的学习中，小松学到了“有序对”这么一个概念，即用&lt;x, y&gt;表示有序对x和y。要注意的是有序对&lt;x, y&gt;不等于有序对&lt;y, x&gt;。对于一个有序对集合R={&lt;x,y&gt;, &lt;y, z&gt;, &lt;x,  z&gt;，……}，我们说R是传递的，当且仅当他满足下面的性质：</p>
<p> </p>
<p><strong>红色字体用直观的语言描述是：如果存在&lt;x, y&gt;</strong><strong>∈R</strong><strong>，&lt;y, z&gt;</strong><strong>∈R</strong><strong>，那么一定存在&lt;x, z&gt;</strong><strong>∈R</strong><strong>。</strong></p>
<p><strong> </strong></p>
<p>       这里集合R可以对应到一个有向图G，有序对&lt;x ,y&gt;对应到了G中的一条有向边。 你现在的任务是，对于任意给定的一个简单有向图G（同一有向边不出现两次），判断G是否具有传递性。</p>
<p> </p>

<img src="/source/codevs/codevs-1019/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMDE5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMDE5LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入文件set.in第一行包含测试数据的个数T(1&lt;=T&lt;=10)。接下来T组测试数据，每组测试数据第一行包含两个个整数n和m（1&lt;=n&lt;=1000, n&lt;=m&lt;=100000），表示G中元素个数和有向边的个数，接下来的m行每行2个整数x, y（1&lt;=x,y&lt;=n）表示x与y之间有一条有向边连接。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;对于每组数据，如果G是传递的，你需要向输出文件set.out输出一行&rdquo;Yes&rdquo;, 否则输出一行&rdquo;No&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>3 3</p>
<p>1 2</p>
<p>1 3</p>
<p>2 3</p>
<p>4 5</p>
<p>1 2</p>
<p>1 3</p>
<p>1 4</p>
<p>2 3</p>
<p>3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes</p>
<p>No</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>有30%满足1&lt;=n&lt;=100, 1&lt;=m&lt;=10000;</p>
<p>有100%的数据满足1&lt;=n&lt;=1000, 1&lt;=m&lt;=100000;</p>
</div>
</div>