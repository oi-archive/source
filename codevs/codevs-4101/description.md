<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>其实aby890是一个十分爱干净的孩子，最近aby890迷恋上了泡泡浴。</p><p>迷恋泡泡浴的原因除了泡泡特别好玩之外，还由于洗泡泡浴的浴缸十分奇怪，这是个地面参差不齐的浴缸。我们可以把浴缸看成N*M的矩阵，那么矩阵上的每个元素为该位置浴缸的高度。</p><p>由于水往低处流，相邻的格子的水面高度不同，高处的水会往低处去。</p><p>浴缸当然要有出水口，出水口在某个格子上。而且浴缸的边缘可以看作无穷高。</p><p>然后大家肯定会发现，洗完泡泡浴后，把水放掉后，可能有些地方会积水。即水不能通过出水口流出。</p><p>aby890就是喜欢看看这些积水。aby890测量了一下，自己放水之前浴缸的所有位置的水面高度均为K(除了浴缸底部高度大于K的格子)。如果浴缸底部高度大于K，那么这个格子没有水，水面高度可以当作是浴缸底部高度。</p><p>然后aby890打开了出水口。</p><p>请你帮aby890预测一下，当出水口不再出水了，浴缸每个格子的剩余的水高度是多少。</p><p>(剩余的水的高度=水面高度-浴缸底部高度)</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入第一行仅包含三个整数</span>N,M,K<span style="">，表示浴缸的大小与初始每个格子的水面高度。</span> </p><p><span style="">接下来</span>N<span style="">行，每行</span>M<span style="">个整数，表示每个格子浴缸底部的高度</span>A[i,j]<span style="">。</span></p><p><span style="">接下来一行两个数</span>r<span style="">和</span>c<span style="">，表示出水口的行和列。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">输出</span>N<span style="font-family:宋体">行</span>,<span style="font-family:宋体">每行包含</span>M<span style="font-family:宋体">个整数，表示每个格子的剩余水的高度。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">3 3 66</p><p style="">6 9 1</p><p style="">7 8 1</p><p style="">6 8 1</p><p style="">3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 0 7</p><p>1 0 7</p><p>2 0 7</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于40%的数据N,M&lt;=100  A[I,j]&lt;=100</p><p>对于70%的数据N,M&lt;=500 </p><p>对于100%的数据N,M&lt;=800  A[I,j]&lt;=10000</p>
</div>
</div>