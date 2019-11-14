<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">机器人 Rob 可在一个树状路径上自由移动。给定树状路径 T 上的起点 s 和终点 t，机器</span><span style="">人 Rob 要从 s 运动到 t。树状路径 T 上有若干可移动的障碍物。由于路径狭窄，任何时刻在</span><span style="">路径的任何位置不能同时容纳 2 个物体。每一步可以将障碍物或机器人移到相邻的空顶点</span><span style="">上。设计一个有效算法用最少移动次数使机器人从 s 运动到 t。 </span><br><br><span style="">对于给定的树 T，以及障碍物在树 T 中的分布情况。计算机器人从起点 s 到终点 t 的最</span><span style="">少移动次数。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第 1 行有 3 个正整数 n，s 和 t，分别表示树 T 的</span><span style="">顶点数，起点 s 的编号和终点 t 的编号。 </span><br><span style="">接下来的 n 行分别对应于树 T 中编号为 0，1，…，n-1 的顶点。每行的第 1 个整数 h</span><span style="">表示顶点的初始状态，当 h=1 时表示该顶点为空顶点，当 h=0 时表示该顶点为满顶点，其</span><span style="">中已有 1 个障碍物。第 2 个数 k 表示有 k 个顶点与该顶点相连。接下来的 k 个数是与该顶点</span><span style="">相连的顶点编号。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: large;">计算出的机器人最少移动次数，如果无法</span><span style="font-size: large;">将机器人从起点移动到终点，输出&ldquo;No solution！&rdquo;。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5 0 3 </span></p>
<p><span style="">1 1 2 </span></p>
<p><span style="">1 1 2 </span></p>
<p><span style="">1 3 0 1 3 </span></p>
<p><span style="">0 2 2 4 </span></p>
<p><span style="">1 1 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>