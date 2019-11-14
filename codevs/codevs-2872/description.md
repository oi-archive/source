<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小吴在国防学校军训了两天两夜。在Wikioi上刷题成瘾的小吴实在无法抗拒刷题的诱惑，他趁着晚上的黑暗逃出了学校。</p>
<p>小吴有一张地图，上面1号点是国防学校，N号点是小吴家。（共有N个点）</p>
<p>不幸的是，k个教官（每个有编号，教官只会走第K个岔路口，若没有，走向最后一个，教官绝不会走回头路）在T分钟后出来追他。教官的速度是V每分钟，小吴速度是W。V一定比W快，所以小吴想回家刷题是不现实的。</p>
<p>但有P个网吧，它们分别在点Ai。</p>
<p>小吴必须在教官到网吧前1分钟离开网吧，在教官到他家前1分钟返回国防学校。</p>
<p>求小吴最多能刷题几分钟？</p>
<p>（保证答案有限）（走一段路的时间需上取整）</p>
<p> （编号以邻接矩阵从左向右的顺序为准）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>N T P V W</p>
<p>邻接矩阵（带权）</p>
<p>Ki（每种教官是否存在，用0或1表示，总数为1号点的出度）</p>
<p>Ai</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>最长时间</p>
<p>若无法刷题，输出Oh，my god!I will die!!</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 1 3 2</p>
<p>0 2 3 0</p>
<p>2 0 1 0</p>
<p>3 1 0 4</p>
<p>0 0 4 0</p>
<p>1 0</p>
<p>2</p>

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
<p>N&lt;=400,P&lt;=100.</p>
</div>
</div>