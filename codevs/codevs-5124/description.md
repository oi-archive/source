<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">Lucius 掌握了一种神奇的传送魔法，这可以让他完成任意距离的瞬移。然而魔法学院校长对他的移动做了一定的限制，让他只能在 1 到 n 的整点位置移动，同时在位置 b 处设下法阵，使得 Lucius 的每次移动目的地 y 与出发点 x 之间的关系必须满足 |x-b|&gt;|x-y| 。 经过了这样的限定， Lucius 的移动方式就变得非常有限。他想知道从 a 点出发，经过 k 次移动一共能有几种移动方式。我们认为在移动中产生的序列有一位不同则可视为不同的移动方式。在传送中，出发点与目的点不能相同，但是答案还是非常庞大，因此需要你对1000000007取模之后再输出。</span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">四个数字 n , a , b  , k , 如题所示。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 微软雅黑, &quot;Microsoft YaHei&quot;;">一行，移动方式数对1000000007取模。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5 2 4 2</span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例说明】两种传送方式为 2—1—2 和 2—1—3。</span></p><p><span style=""></span></p><hr><p><span style="">对于 30% 的数据 1 ≤ n ,  k ≤ 10；</span></p><p><span style="">对于 60% 的数据 1 ≤ n , k ≤ ≤ 300 ；</span></p><p><span style="">对于 100% 的数据 1 ≤ n , k ≤ 5000 , 1 ≤ a, b ≤ n。</span></p>
</div>
</div>