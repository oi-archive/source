<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明要搬家了，大家都来帮忙。 小明现在住在第N楼，总共K个人要把X个大箱子搬上N楼。 最开始X个箱子都在1楼，但是经过一段混乱的搬运已经乱掉了。最后，大家发现这样混乱的搬运过程效率太低了，于是总结出了提高效率的方法。大家的速度都是每分钟上或下层楼。多余向上走的人手中都拿一个箱子，所有向下走的人手中都不拿箱子。到达第N层立刻放下箱子向下走，到达第1层立刻拿起箱子向上走。当一个人向上走，另一个人向下走而在楼道相遇时，向上走的人将手中的箱子交割另一个人，两人同时反向。即原来拿箱子向上走的人不拿箱子往下走。原来不拿箱子向下走的人现在拿着箱子向上走。 求将所有箱子搬完所需的最短时间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行N（N≤10^9），K（K≤500000），M（M≤10^9），分别比表示楼层数、人数、还放在一楼地上的箱子数。 接下来K行，每行两个数Ai，Bi。 Ai表示第i人现所在的楼层数，Bi为0或1.，为0表示第i人正拿着箱子往上走，为1表示第i人不拿箱子向下走。 输入满足没有任意两个人正在同一楼层，在第1层的人一定正拿着箱子向上走，在第N层的人一定正不拿着箱子向下走</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个整数，为搬完箱子的时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2 4</p>
<p>1 0</p>
<p>3 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p>
<p>对于30%的数据有K≤100，M≤100</p>
<p>对于60%的数据有K≤1000，M≤109</p>
<p>对于100%的数据有K≤500000，M≤109</p>
</div>
</div>