<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>终于到达了这次选拔赛的最后一题，想必你已经厌倦了小蓝和小白的故事，为了回馈各位比赛选手，此题的主角是贯穿这次比赛的关键人物——小蓝的好友。</p>
<p>在帮小蓝确定了旅游路线后，小蓝的好友也不会浪费这个难得的暑假。与小蓝不同，小蓝的好友并不想将时间花在旅游上，而是盯上了最近发行的即时战略游戏——<span style="font-family: Calibri;">SangoCraft</span><span style="">。但在前往通关之路的道路上，一个小游戏挡住了小蓝的好友的步伐。</span></p>
<p>“国家的战争其本质是抢夺资源的战争”是整款游戏的核心理念，这个小游戏也不例外。简单来说，用户需要在给定的长方形土地上选出一块子矩形，而系统随机生成了<span style="font-family: Calibri;">N</span><span style="">个资源点，位于用户所选的长方形土地上的资源点越多，给予用户的奖励也越多。悲剧的是，小蓝的好友虽然拥有着极其优秀的能力，但同时也有着极差的</span><span style="font-family: Calibri;">RP</span><span style="">，小蓝的好友所选的区域总是没有一个资源点。</span></p>
<p>终于有一天，小蓝的好友决定投诉这款游戏的制造厂商，为了搜集证据，小蓝的好友想算出至少包含一个资源点的区域的数量。作为小蓝的好友，这自然是你分内之事。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每个输入文件中仅包含一个测试数据。</p>
<p>第一行包含两个由空格隔开的正整数<span style="font-family: Calibri;">R,C,N</span><span style="">，表示游戏在一块</span><span style="font-family: Calibri;">[1,R]X[1,C]</span><span style="">的地图上生成了</span><span style="font-family: Calibri;">N</span><span style="">个资源点。</span></p>
<p>     接下来有<span style="font-family: Calibri;">N</span><span style="">行，每行包含两个整数 </span><span style="font-family: Calibri;">x,y</span><span style="">，表示这个资源点的坐标</span><span style="font-family: Calibri;">(1&lt;=x&lt;=R,1&lt;=y&lt;=C</span>)<span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp;输出文件应仅包含一个整数，表示至少包含一个资源点的区域的数量。具体的说，设<span style="font-family: Calibri;">N</span><span style="font-family: 宋体;">个资源点的坐标为</span>(i=1..n),<span style="font-family: 宋体;">你需要计算有多少个</span>四元组<span style="font-family: Calibri;">(LB,DB,RB,UB)</span><span style="font-family: 宋体;">满足</span>，且存在一个<span style="font-family: Calibri;">i</span><span style="font-family: 宋体;">使得</span>均成立。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 4</p>
<p>1 2</p>
<p>2 3</p>
<p>3 5</p>
<p>4 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>139</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>对于<span style="font-family: Calibri;">20%</span><span style="">的数据，N&lt;=50</span></p>
<p>对于<span style="font-family: Calibri;">40%</span><span style="">的数据，N&lt;=2000</span></p>
<p>对于<span style="font-family: Calibri;">100%</span><span style="">的数据，R,C&lt;=40000 N&lt;=100000</span>，资源点的位置两两不同，且位置为随机生成。</p>
</div>
</div>
</div>