<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    有一个有趣得取数游戏。初始时，给出一个环，环上得每条边上都有一个非负整数。这些整数中至少有一个时0。然后，将一枚硬币放在环上得一个节点上。二个玩家就是以这个放硬币得节点为起点开始这个游戏，二人轮流取数，取数得规则如下：</p>
<p>    （1）选择硬币左边或右边得一条边，并且边上得数非0；</p>
<p>    （2）将这条边上的数减至任意一个非负整数（至少要有所减小）；</p>
<p>    （3）将硬币移到边的另一端。</p>
<p>    如果轮到一个玩家走，这时硬币左右两边的边上的数值都是0，那么这个玩家就输了。</p>
<p>    如下图所示，描述的时爱丽思和鲍勃两人的对弈过程，其中黑色节点表示硬币所在节点，结果图（d）中，轮到鲍勃走时，硬币两边的边上都是0。所以爱丽思获胜。</p>
<p> </p>
<p>    现在你的任务是根据给出的环、边上的数值以及起点（硬币所在位置），判断先走方是否有必胜的策略。</p>

<img src="/source/codevs/codevs-1037/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMDM3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMDM3LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入：第行一个整数N（N&lt;=20），表示环上的节点数。</p>
<p>    第2行N个数，数值不超过30，依次表示N条边上的数值。硬币的起始位置是第一条边与最后一条边之间的节点上。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp; &nbsp;输出：仅1行。若存在必胜策略，则输出&lsquo;YES&rsquo;，否则输出&lsquo;NO&rsquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1:</p>
<p>4</p>
<p>2  5  3  0</p>
<p> </p>
<p>样例2:</p>
<p>3</p>
<p>0  0  0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1:</p>
<p>YES</p>
<p> </p>
<p>样例2:</p>
<p>NO</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
如描述
</div>
</div>