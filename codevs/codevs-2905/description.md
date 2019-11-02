<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>A市举行了一场足球比赛</p>
<p>一共有4n支队伍参加，分成n个小组（每小组4支队伍）进行小组循环赛（胜积3分，平积1分，负不计分）</p>
<p>(晋级的球队积分最高)</p>
<p>问晋级的队伍是那些？</p>
<p>PS：每小组只能晋级一支球队</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：一个整数n（保证是四的倍数）</p>
<p>换行读入队伍名</p>
<p>接下来读入比分</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>换行输出每支队伍的名字</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>King</p>
<p>Soon</p>
<p>River</p>
<p>Ken</p>
<p>King 1:0 Soon</p>
<p>Soon 1:3 River</p>
<p>Ken 0:0 River</p>
<p>King 9:0 River</p>
<p>Soon 7:3 Ken</p>
<p>King 4:1 River</p>
<p>Blue</p>
<p>Son</p>
<p>Rivr</p>
<p>Ke</p>
<p>Blue 1:0 Son</p>
<p>Son 1:3 Rivr</p>
<p>Ke 0:0 Rivr</p>
<p>Blue 4:3 Rivr</p>
<p>Son 7:3 Ke</p>
<p>Blue 4:1 Rivr</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>King</p>
<p>Blue</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>保证每个小组只有一支队伍晋级</p>
<p>1&lt;=n&lt;=100</p>
</div>
</div>