<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><span style="font-family: Calibri;"> </span><span style="">堆，是一种神奇的数据结构</span> <span style="font-family: Calibri;"> </span><span style="">不寂寞的堆，是一棵满二叉树，其儿子节点的</span><span style="font-family: Calibri;">key</span><span style="">值都不大于父亲节点的</span><span style="font-family: Calibri;">key</span><span style="">值</span> <span style="font-family: Calibri;"> </span><span style="font-family: Calibri;">  </span><span style="">久而久之，不寂寞的堆寂寞了，它不满足于自己这无聊又乏味的性质，于是它提出要求，在自己本身性质的基础上，对于堆中任意一个非叶子节点，它的左子树中任意节点的</span><span style="font-family: Calibri;">key</span><span style="">值都不能大于其右子树任意节点的</span><span style="font-family: Calibri;">key</span><span style="">值</span> <span style="font-family: Calibri;"> </span><span style="font-family: Calibri;">  </span><span style="">我们称满足上述两个条件的满二叉树为寂寞的堆</span> <span style="font-family: Calibri;"> </span><span style="font-family: Calibri;">  </span><span style="">给定你一棵满二叉树，询问最少修改多少个节点的</span><span style="font-family: Calibri;">key</span><span style="">值，才能使它变成寂寞的堆</span></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是层数 表示完全二叉树共n层<br></p><p>之后每一行表示该i层所有叶子节点的值</p><p>可能有数据稍大 推荐开long long</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>最小的k值<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>2 </p><p>1 2 </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>dp</p><p>n&lt;=18</p><p>对于30%的数据 n&lt;=2<br></p><p>对于60%的数据 n&lt;=10</p>
</div>
</div>