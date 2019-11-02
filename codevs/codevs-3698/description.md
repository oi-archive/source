<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">很久很久之前，森林里住着一群兔子。有一天，兔子们突然决定要去看樱花。兔子们所在森林里的樱花树很特殊。樱花树由</span>n<span style="">个树枝分叉点组成，编号从</span>0<span style="">到</span>n-1<span style="">，这</span>n<span style="">个分叉点由</span>n-1<span style="">个树枝连接，我们可以把它看成一个有根树结构，其中</span>0<span style="">号节点是根节点。这个树的每个节点上都会有一些樱花，其中第</span>i<span style="">个节点有</span>c_i<span style="">朵樱花。樱花树的每一个节点都有最大的载重</span>m<span style="">，对于每一个节点</span>i<span style="">，它的儿子节点的个数和</span>i<span style="">节点上樱花个数之和不能超过</span>m<span style="">，即</span>son(i) + c_i &lt;= m<span style="">，其中</span>son(i)<span style="">表示</span>i<span style="">的儿子的个数，如果</span>i<span style="">为叶子节点，则</span>son(i) = 0</p><p style=""><span style="">现在兔子们觉得樱花树上节点太多，希望去掉一些节点。当一个节点被去掉之后，这个节点上的樱花和它的儿子节点都被连到删掉节点的父节点上。如果父节点也被删除，那么就会继续向上连接，直到第一个没有被删除的节点为止。</span></p><p style=""><span style="">现在兔子们希望计算在不违背最大载重的情况下，最多能删除多少节点。</span></p><p style=""><span style="">注意根节点不能被删除，被删除的节点不被计入载重。</span></p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行输入两个正整数，</span><span style="">n</span><span style="">和</span><span style="">m</span><span style="">分别表示节点个数和最大载重</span><span style="">第二行</span><span style="">n</span><span style="">个整数</span><span style="">c_i</span><span style="">，表示第</span><span style="">i</span><span style="">个节点上的樱花个数</span><span style="">接下来</span><span style="">n</span><span style="">行，每行第一个数</span><span style="">k_i</span><span style="">表示这个节点的儿子个数，接下来</span><span style="">k_i</span><span style="">个整数表示这个节点儿子的编号</span><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体; text-indent: 28px;">一行一个整数，表示最多能删除多少节点。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Helvetica, sans-serif;">1</span>0 4</p><p style="">0 2 2 2 4 1 0 4 1 1</p><p style="">3 6 2 3</p><p style="">1 9</p><p style="">1 8</p><p style="">1 1</p><p style="">0</p><p style="">0</p><p style="">2 7 4</p><p style="">0</p><p style="">1 5</p><p style="">0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
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
<p style=""><span style="">对于</span>30%<span style="">的数据，</span>1 &lt;= n &lt;= 5000, 1 &lt;= m &lt;= 100, 0 &lt;= c_i &lt;= 100</p><p style=""><span style="">对于</span>70%<span style="">的数据，</span>1 &lt;= n &lt;= 200000, 1 &lt;= m &lt;= 2000, 0 &lt;= c_i &lt;= 1000</p><p style=""><span style="">对于</span>100%<span style="">的数据，</span>1 &lt;= n &lt;= 2000000, 1 &lt;= m &lt;= 100000, 0 &lt;= c_i &lt;= 1000</p><p style=""><span style="">数据保证初始时，每个节点樱花数与儿子节点个数之和大于</span>0<span style="">且不超过</span>m</p><p><br></p>
</div>
</div>