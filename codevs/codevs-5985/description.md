<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><br></p><p>作为一个强迫症患者，谢榛在走游戏里的迷宫时一定要把所有的宝箱收集齐</p><p>才肯罢休。</p><p>现在给你一个 N×M 的迷宫，里面有障碍、空地和宝箱，谢榛在某个起始点，每一步谢榛可以往上下左右走， 当然前提是没有走出迷宫并且走到的点不是障碍。如果谢榛走到了某个为宝箱的点，那么这个宝箱就被他收集到了，然后此处变为空地。</p><p>现在你需要计算谢榛最少需要走多少步才能收集齐所有的宝箱。</p><p><br></p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""></span></p><p style="">输入共有两行。</p><p style="">第一行一个两个正整数 N 和 M，表示迷宫大小。</p><p style="">接下来 N 行，每行 M 个整数，第 i+1 行的第 j 个整数表示迷宫第 i 行第 j 列的情况，0 表示空地，-1 表示障碍，1 表示宝箱，2 表示谢榛的起始点。保证 2 只有一个。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，包含一个整数，表示谢榛最少的步数。如果谢榛无法收集齐所有宝箱，输出-1</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">3 5</p><p style="">1 -1 1 -1 2</p><p style="">0 -1 0 -1 0</p><p style="">0 0 0 0 0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>40% 宝箱只有一个</p><p>100% 0&lt;N,M&lt;=100, 宝箱个数不超过 5</p><p><br></p>
</div>
</div>