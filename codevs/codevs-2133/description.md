<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>10 年一度的银河系赛车大赛又要开始了。作为全银河最盛大的活动之一，<br>夺得这个项目的冠军无疑是很多人的梦想，来自杰森座 α星的悠悠也是其中之一。 <br>赛车大赛的赛场由 N 颗行星和M条双向星际航路构成，其中每颗行星都有<br>一个不同的引力值。大赛要求车手们从一颗与这 N 颗行星之间没有任何航路的<br>天体出发，访问这 N 颗行星每颗恰好一次，首先完成这一目标的人获得胜利。 <br>由于赛制非常开放，很多人驾驶着千奇百怪的自制赛车来参赛。这次悠悠驾<br>驶的赛车名为超能电驴，这是一部凝聚了全银河最尖端科技结晶的梦幻赛车。作<br>为最高科技的产物，超能电驴有两种移动模式：高速航行模式和能力爆发模式。<br>在高速航行模式下，超能电驴会展开反物质引擎，以数倍于光速的速度沿星际航<br>路高速航行。在能力爆发模式下，超能电驴脱离时空的束缚，使用超能力进行空<br>间跳跃——在经过一段时间的定位之后，它能瞬间移动到任意一个行星。 <br>天不遂人愿，在比赛的前一天，超能电驴在一场离子风暴中不幸受损，机能<br>出现了一些障碍：在使用高速航行模式的时候，只能由每个星球飞往引力比它大<br>的星球，否则赛车就会发生爆炸。 <br>尽管心爱的赛车出了问题，但是悠悠仍然坚信自己可以取得胜利。他找到了<br>全银河最聪明的贤者——你，请你为他安排一条比赛的方案，使得他能够用最少<br>的时间完成比赛。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是两个正整数 N, M。 <br>第二行 N 个数 A1~AN， 其中Ai表示使用能力爆发模式到达行星 i 所需的定位<br>时间。 <br>接下来 M行，每行 3个正整数ui, vi, wi，表示在编号为 ui和vi的行星之间存<br>在一条需要航行wi时间的星际航路。 <br>输入数据已经按引力值排序，也就是编号小的行星引力值一定小，且不会有<br>两颗行星引力值相同。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个正整数，表示完成比赛所需的最少时间。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 <br>1 100 100 <br>2 1 10 <br>1 3 1 <br>2 3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30%的数据 N≤20，M≤50； <br>对于 70%的数据 N≤200，M≤4000； <br>对于100%的数据N≤800， M≤15000。输入数据中的任何数都不会超过106<br>。 <br>输入数据保证任意两颗行星之间至多存在一条航道，且不会存在某颗行星到<br>自己的航道。</p>
</div>
</div>