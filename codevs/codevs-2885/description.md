<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个三角形木板,竖直立放，上面钉着n(n+1)/2颗钉子，还有(n+1)个格子（当n=5时如图1）。每颗钉子和周围的钉子的距离都等于d，每个格子的宽度也都等于d，且除了最左端和最右端的格子外每个格子都正对着最下面一排钉子的间隙。</p>
<p>让一个直径略小于d的小球中心正对着最上面的钉子在板上自由滚落，小球每碰到一个钉子都可能落向左边或右边（概率各1/2），且球的中心还会正对着下一颗将要碰上的钉子。例如图2就是小球一条可能的路径。</p>
<p>现在的问题是计算拔掉某些钉子后，小球落在编号为m的格子中的概率pm。假定最下面一排钉子不会被拔掉。例如图3是某些钉子被拔掉后小球一条可能的路径。</p>

<img src="/source/codevs/codevs-2885/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzI4ODVfMS5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行为整数n（2&lt;=n&lt;=50）。</p>
<p>以下n行依次为木板上从上至下n行钉子的信息，每行中‘*’表示钉子还在，‘.’ 表示钉子被拔去(最下面一排的钉子不会拔掉)，注意在这n行中空格符可能出现在任何位置。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">共n+1行，每一行是一个既约分数(0写成0/1)，为小球落在编号为0到编号为n这n+1个的格子中的概率m。</p>
<p class="p0">既约分数的定义：A/B是既约分数，当且仅当A、B为正整数且A和B没有大于1的公因子。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>*</p>
<p>* *</p>
<p>* . *</p>
<p>* * * *</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1/16</p>
<p>1/8</p>
<p>5/8</p>
<p>1/8</p>
<p>1/16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>（2&lt;=n&lt;=50）</p>
</div>
</div>