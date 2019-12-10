<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>众所周知，LOL这款伟大的游戏，有个叫盖伦的英雄。他的伟大之处在于他特别喜欢蹲草丛阴人（XL：蹲草阴人也算英雄？！CZQ：没办法，个个都是这么玩的）。某日，德玛西亚与诺克萨斯之间又发生了一场战斗，嘉文四世希望盖伦能带领一支K人的德玛西亚军队出战。</p>
<p>战斗发生在召唤师峡谷。整个召唤师峡谷被分割成M行N列的一个矩阵，矩阵中有空地和几片草丛。这几片草丛中有些很大、有些很小。一个1×1的草丛能容纳3个士兵，盖伦坚信蹲草偷袭战术能战胜诺克萨斯军队，所以他希望他的军队能全部蹲进草丛里。当然，为了不影响盖伦的作战，盖伦需要单独霸占连起来的一片草丛（不管草丛有多大）。</p>

<img src="/source/codevs/codevs-2801/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzI4MDEuanBn.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行M、N、K，表示矩阵的行数、列数和士兵数量。<br>接下来M行，输入矩阵，'.'代表平地，'*'代表草丛。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果德玛西亚军队和盖伦都能躲进草丛里，则输出&ldquo;Demacia Win!&rdquo;，否则输出&ldquo;Demacia Lose!&rdquo;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 6<br>.**<br>...<br>.*.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Demacia Win!</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=m、n&lt;=1500<br>1&lt;=k&lt;=1500<br>P.S：这里对于两个1×1的草丛是否连在一起的定义是：对于每个1×1的草从，它与周围（上下左右）的草丛是连在一起的。</p>
</div>
</div>