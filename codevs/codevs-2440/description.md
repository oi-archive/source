<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个<em>r</em>行<em>c</em>列的网格地图中有一些高度不同的石柱，一些石柱上站着一些蜥蜴，你的任务是让尽量多的蜥蜴逃到边界外。</p>
<p>每行每列中相邻石柱的距离为1，蜥蜴的跳跃距离是<em>d</em>，即蜥蜴可以跳到平面距离不超过<em>d</em>的任何一个石柱上。石柱都不稳定，每次当蜥蜴跳跃时，所离开的石柱高度减1（如果仍然落在地图内部，则到达的石柱高度不变），如果该石柱原来高度为1，则蜥蜴离开后消失。以后其他蜥蜴不能落脚。任何时刻不能有两只蜥蜴在同一个石柱上。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为三个整数<em>r</em>，<em>c</em>，<em>d</em>，即地图的规模与最大跳跃距离。以下<em>r</em>行为石竹的初始状态，0表示没有石柱，1~3表示石柱的初始高度。以下<em>r</em>行为蜥蜴位置，“L”表示蜥蜴，“.”表示没有蜥蜴。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行，包含一个整数，即无法逃离的蜥蜴总数的最小值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 8 2</p>
<p>00000000</p>
<p>02000000</p>
<p>00321100</p>
<p>02000000</p>
<p>00000000</p>
<p>........</p>
<p>........</p>
<p>..LLLL..</p>
<p>........</p>
<p>........</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据满足：1&lt;=<em>r</em>, <em>c</em>&lt;=20, 1&lt;=<em>d</em>&lt;=3</p>
</div>
</div>